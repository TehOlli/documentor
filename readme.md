# Generate documentation
1. Install phpDocumentor
2. Add this template folder to `data/tempalte` in the root of your project
3. Move `phpdoc.dist.xml` and `generate-hooks.php` to the root of your project
4. Change the title tag in `phpdoc.dist.xml` to match your project
6. Modify `generate-hooks.php` to define the paths where to look for filters/actions
7. Run command `php {documentor path} -d . -t docs/api --template=".phpdoc/template" --sourcecode`
8. Run command `php generate-hooks.php` to generate filter/action reference