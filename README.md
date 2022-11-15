# gz-rcll
Escenario para robocup logistics en gazebo ignition.

La base para los modelos y los _plugins_ proviene de [gazebo-rcll](https://github.com/robocup-logistics/gazebo-rcll).

# gz-rcll-models
Para invocar gazebo y visualizar el mundo por defecto se puede utilizar el siguiente comando:

```
ros2 launch gz_rcll_models defaultworld.launch.py v:='3'
```
Éste se encargará de que gazebo detecte los recursos en el directorio de instalación.