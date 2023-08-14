
pex_binary(
    name = 'binary2',
    entry_point = 'binary2.cli',
    dependencies = [
    ],
)

python_tests(
    # name defaults to the name of the directory the BUILD file is in `tests`
    # sources defaults to ['*_test.py', 'test_*.py', 'conftest.py'].
    sources=['tests/test_*.py'],
    dependencies = [
        "src/python/binary_project2:binary2",
    ]
)