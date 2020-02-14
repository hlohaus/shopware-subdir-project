# Shopware 6 - Subdir Project

Install Shopware in a sub directory. It use same code, but no the same database.
So you can test plugins.

1.) Install subdir project

    mkdir public/your_subdir
    cd public/your_subdir
    git clone https://github.com/hlohaus/shopware-subdir-project.git .
    
2.) Copy database

3.) Copy .env to private/

4.) Change database name in .env

5.) Link folders

    ln -s ../bundles/ .
    ln -s ../media/ .
    ln -s ../theme/ .
    ln -s ../thumbnail/ .
    
6.) Open storefront
