1.) Install subdir project

    mkdir public/you_subdir
    cd public/your_subdir
    git clone https://github.com/hlohaus/shopware-subdir-project.git .
    
2.) Copy database
3.) Copy .env to private/
4.) Change database name in .env
5.) Link folders

    ln -s ../bundels/ .
    ln -s ../media/ .
    ln -s ../theme/ .
    ln -s ../thumbnail/ .
    
6.) Open storefront
