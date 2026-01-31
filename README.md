<pre>
# odoo_custom_scaffold
Allows you to scaffold a customized template of your choice

Directory (as per Odoo default)

  default/
  ├── controllers
  │   ├── __init__.py.template
  │   └── controller.py.template
  ├── demo
  │   └── demo.xml.template
  ├── models
  │   └── __init__.py.template
  │   └── models.py.template
  ├── security
  │   └── ir.model.access.csv.template
  ├── views
  │   └── templates.xml.template
  │   └── views.xml.template
  ├── __init__.py.template
  ├── __manifest__.py.template

Add/Remove/Update the files in the directory that is subjected to the types ['.py', '.xml', '.csv', '.txt', '.md', '.json']

How to use

1. Git clone this inside your pycharm environment
2. cd into the file
3. use this command python ./scaffold <custom_module_name> <custom_addons_path>
4. Done

</pre>
