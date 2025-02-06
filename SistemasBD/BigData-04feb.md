# **HDFS CLUSTER**

## **Parte de preparacion del nodo**

IPs y nombres de los hosts

![1738697661800](images/BigData-04feb/1738697661800.png)

![1738697812641](images/BigData-04feb/1738697812641.png)

![1738697877565](images/BigData-04feb/1738697877565.png)

Versión Java

![1738698123060](images/BigData-04feb/1738698123060.png)

Fichero authorizes-keys de todos los hosts

![1738698333819](images/BigData-04feb/1738698333819.png)

lsblk de los nodos

![1738698407679](images/BigData-04feb/1738698407679.png)

## **Configuracion de Hadoop**

Ver variables HADOOP_HOME y PATH del namenode

![1738698503705](images/BigData-04feb/1738698503705.png)

Configuración del archivo core-site.xml en cada nodo.

![1738698710600](images/BigData-04feb/1738698710600.png)

## **Namenode sin ser datanode**

Configuración del archivo hdfs-site.xml en cada nodo.

![1738698996689](images/BigData-04feb/1738698996689.png)

Información del sistema hdfs, espacio disponible

![1738699121746](images/BigData-04feb/1738699121746.png)

Crear algunas carpetas y subir algún fichero grande a alguna de ellas

![1738699560310](images/BigData-04feb/1738699560310.png)

Mostrar la estructura y algún fichero con bloques replicados y en que nodos están

![1738699460833](https://file+.vscode-resource.vscode-cdn.net/c%3A/Users/IABD/Desktop/images/BigData-04feb/1738699460833.png)![1738699437417](https://file+.vscode-resource.vscode-cdn.net/c%3A/Users/IABD/Desktop/images/BigData-04feb/1738699437417.png)


## **Namenode siendo datanode**

Mostrar archivo hdfs-site.xml de ese hosts. Mostrar archivo Workers.

![1738699822532](images/BigData-04feb/1738699822532.png)

![1738699879299](images/BigData-04feb/1738699879299.png)

Eliminar el fichero de antes y volverlo a subir

![1738700003724](images/BigData-04feb/1738700003724.png)

Mostrar de nuevo en un navegador los nodos activos y los bloques que ocupa el fichero

![1738700044042](images/BigData-04feb/1738700044042.png)

![1738700074848](images/BigData-04feb/1738700074848.png)

Modificar hdfs-site.xml para disminuir el tiempo de latencia de comprobación de nodos activos y mostrar esa configuración

![1738700501797](images/BigData-04feb/1738700501797.png)

Decomisar un host que no sea el namenode

![1738700574550](images/BigData-04feb/1738700574550.png)

Mostrar en el navegador la nueva situación y como ha replicado los bloques de nuevos

![1738700792544](images/BigData-04feb/1738700792544.png)

![1738701018570](images/BigData-04feb/1738701018570.png)
