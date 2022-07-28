# Each subdirectory is a self contained and packaged project using Poetry to manage the environment and dependencies

For example: fast_is_fast_enough is a usecase of profiling python to code to find bottle necks and help gauge when more advanced solutions than the standard python DS stack is required.

In order to interact with these environments there is one dependency: [Poetry](https://python-poetry.org/)

After install Poetry navigate to the top level of one of the subdirectories and exec ```poetry install``` to create and install the environment described in the project .toml file and then ```poetry shell``` to activate the env.

