# conda_recipes
Conda recipes I created for other tools.

# Command to build conda package
```bash
conda mambabuild <recipe_folder>
conda convert --platform osx-64 </path/to/package.tar.bz2> -o <outputdir/>
anaconda upload <converted_package>
```