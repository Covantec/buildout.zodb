buildout.zodb
=============

Configuración de buildout para instalar una aplicación Python con utilidades de ZODB.

Requerimientos
==============

Estos son los requerimientos mínimos de instalación: ::

  # apt-get install python-pip
  # pip install virtualenv ; exit

Crear entorno virtual
=====================

Para la inicialización del proyecto Buildout, ejecute el siguiente comando: ::

  $ virtualenv python2.7
  $ source ./python2.7/bin/activate

Inicialización del proyecto
===========================

Para la inicialización del proyecto Buildout, ejecute el siguiente comando: ::

  (python2.7)$ python bootstrap.py

Construcción del proyecto
=========================

Para la construcción del proyecto Buildout, ejecute el siguiente comando: ::

  (python2.7)$ ./bin/buildout

ZODB en Python
==============

Para manipular la base de datos ZODB en lenguaje programación Python, ejecute el siguiente comando: ::

  ./bin/python
  >>> import ZODB
  >>>

