#python_distribution(
#    name = 'library2',
#    wheel=True,
#    sdist=True,
#    dependencies = [
#    ],
#    provides=setup_py(
#        name="library2",
#        version="1.0.0",
#        description="Library test 2",
#    ),
#)

python_sources(name="lib2", sources=["library2/*.py"])
resource(name="pyproject", source="pyproject.toml")

python_distribution(
    name="library2",
    dependencies=[":pyproject", ":lib2"],
    generate_setup=False,
    provides=python_artifact(name="library2", version="1.0.0"),
    sdist=False,
)