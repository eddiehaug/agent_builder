# Set the preferred Python version for creating venvs

poetry env use <path-to-python-version>

# Configure creating venvs inside the project folder

poetry config virtualenvs.in-project true

# Create a virtual env

poetry install

# Check info about the env

poetry env info

# Print the path to the env

poetry env info -p

# Work within the venv (activate env)

poetry env activate

#Copy paste the command printed on the screeen to activate the env.

# Add a package

poetry add <package-name> # for example, poetry add requests

# Remove a package

poetry remove <package-name>

# Deactivate and exit env

deactivate

# Remove venv

poetry env remove
