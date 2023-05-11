# AUTOMATED DATABASE IMPORTATION SCRIPT
    This is a set of scripts made for usage on MacOS and certain Linux Distros.

# What does the script do?
    For first time setup the script will do the following steps:
    -Initiate ddev config
    -Start up the local environment
    -rename the database file to "currentdb.sql.gz" and import it
    -Initiate cache refresh
    -Enable and set the stage file proxy settings feature
    -Initiate second cache refresh
    -Display local environment status(docker information)
    
# Make sure your local has the following:
    -DOCKER(Have it running prior to using the dbsetup script)
    -The database file in the local sites directory
    -Check if you have "usr/local/bin"(If you don't the script installer can help create it)

# Instructions
    For Installing globally
        -With terminal open in the directory, run installer script using /bash installer.
        -You should be able to use "dbsetup" command to run the setup

    To manually run the dbsetup script you can simply do "/bash dbsetup"
    (NOTICE: IF you manually run the script it is best to place the script in the same directory as your local for simplicity)