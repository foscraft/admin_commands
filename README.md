# I compiled all django-admin commands for the new users to try and master them

**Here is the list of all django-admin commands with a brief description.**

    django-admin check                       
Checks the entire Django project for potential problems

    django-admin changepassword <username>   
Allows changing a user’s password. It prompts you to enter a new password twice for the given user.

    django-admin clearsessions               
Can be run as a cron job or directly to clean out expired sessions.

    collectstatic               
Helps to collect all the static files in the one mentioned directory

    django-admin createsuperuser             
Creates a superuser account (a user who has all permissions)

    django-admin compilemessages             
Compiles .po files to .mo files for use with builtin gettext support

    django-admin createcachetable            
Creates the tables needed to use the SQL cache backend.

    django-admin dbshell                     
Runs the command-line client for a specified database, or the default database if none is provided.

    django-admin diffsettings                
Displays differences between the current settings.py and Django's default settings.

    django-admin dumpdata                    
Output the contents of the database as a fixture of the given format (using each model's default manager unless --all is specified).

    django-admin flush                       
Removes ALL DATA from the database, including data added during migrations. Does not achieve a "fresh install" state.

    django-admin inspectdb                   
Introspects the database tables in the given database and outputs a Django model module.

    django-admin loaddata                    
Installs the named fixture(s) in the database.

    django-admin makemessages                
Runs over the entire source tree of the current directory and pulls out all strings marked for translation. It creates (or updates) a message file in the conf/locale (in the Django tree) or locale (for projects and applications) directory. You must run this command with one of either the --locale, --exclude, or --all options.

    django-admin help                        
display usage information and a list of the commands provided by each application

    django-admin makemigrations              
create new migrations to the database based on the changes detected in the models

    django-admin migrate                     
synchronize the database state with your current state project models and migrations

    django-admin remove_stale_contenttypes   
Deletes stale content types (from deleted models) in your database.

    django-admin runserver <port>            
start the development webserver at 127.0.0.1 with the port <port> default 8000

    django-admin sendtestemail               
Sends a test email to the email addresses specified as arguments.

    django-admin shell                       
Runs a Python interactive interpreter. Tries to use IPython or bpython, if one of them is available. Any standard input is executed as code.

    django-admin showmigrations              
Shows all available migrations for the current project.

    django-admin sqlflush                    
Returns a list of the SQL statements required to return all tables in the database to the state they were in just after they were installed.

    django-admin sqlmigrate                  
Prints the SQL statements for the named migration.

    django-admin sqlsequencereset            
Prints the SQL statements for resetting sequences for the given app name(s).

    django-admin squashmigrations            
Squashes an existing set of migrations (from first until specified) into a single new one.

    django-admin startapp <Appname>          
create a new Django application with the specified name

    django-admin startproject <ProjectName>  
create a new project directory structure

    django-admin testserver                  
Runs a development server with data from the given fixture(s).

    django-admin version   
Gives the django version .                  
