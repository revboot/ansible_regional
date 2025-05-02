Revboot/Regional Collection
===========================

Manages Regional resources.

Currently supporting Chrony, Timezone, Locale and Keyboard configuration.

Dependencies
------------

- Python: >=3.10, <3.13
  - Python Packages defined in `requirements.txt`.
- Ansible: >=2.14.0, <2.17.0
  - Ansible Collections defined in `requirements.yml`.
  - Ansible Roles defined in `requirements.yml`.

Example Playbook
----------------

```
    - name: "Manage Regional resources"
      hosts: all
      roles:
        - role: "revboot.regional.chrony"
        - role: "revboot.regional.timezone"
        - role: "revboot.regional.locale"
        - role: "revboot.regional.keyboard"
```

License
-------

This program is free software: you can redistribute it and/or modify  
it under the terms of the GNU General Public License as published by  
the Free Software Foundation, either version 3 of the License, or  
(at your option) any later version.

This program is distributed in the hope that it will be useful,  
but WITHOUT ANY WARRANTY; without even the implied warranty of  
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the  
GNU General Public License for more details.  

You should have received a copy of the GNU General Public License  
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Author Information
------------------

Maintainer: Luís Algarvio <luis.algarvio@revboot.com> https://github.com/lpalgarvio

Copyright Revboot - Tecnologias de Informação e Comunicação, Lda.
