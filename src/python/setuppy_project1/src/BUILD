

pex_binary(
    name = 'setuppy1',
    entry_point = 'setuppy1.cli:main',
    dependencies = [
        ":setuppy1_distribution",
    ],
)


python_distribution(
    name = 'setuppy1_distribution',
    dependencies = [
    ],
    provides=setup_py(
        name="setuppy1",
        version="0.0.1",
        description="An example library built with Pants.",
        author="Pantsbuild",
        classifiers=[
            "Programming Language :: Python :: 3.7",
            "Programming Language :: Python :: 3.8",
        ],
    )
    #.with_binaries(
    #    # Use a dict for multiple entry_points
    #    # https://pants.readme.io/docs/python-setup-py-goal
    #    my_setuppy1_command=":setuppy1",
    #),
)

