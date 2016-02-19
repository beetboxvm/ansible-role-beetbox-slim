# Ansible Role: Beetbox Slim

An Ansible role that creates a Slim project on beetbox.

## Requirements

This role is specifically developed as an extension to beetbox -- https://github.com/beetboxvm/beetbox

## Role Variables

Available variables are listed below, along with default values:

Create new Slim project.

    slim_create_new: no
    
Slim version.    
    
    slim_verison: ""
    
Add example Slim app.    
    
    slim_add_example: no
    
Add Slim .htaccess file.
    
    slim_add_htaccess: no


## Dependencies

- Beetbox -- https://github.com/beetboxvm/beetbox

## License

MIT