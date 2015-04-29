How to setup the app
====================

This assumes that you have ruby(2.2.1) and git installed on your system

1. Open terminal

2. <code>git clone git@github.com:kevivmatrix/athletrak.git</code>

3. <code>cd athletrak</code>

4. bundle

5. <code>cp config/database.example.yml config/database.yml</code> and add your database settings

6. <code>rake db:create && rake db:migrate</code>

7. <code>rails s</code>
