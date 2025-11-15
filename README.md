Trabajo Final 

Se versionaron los manifiestos y las images que se utilizaron para el despliegue del trabajo final.
Se utilizo google cloud para desplegar las aplicaciones y la exposicion de las aplicaciones estan en las siguientes ips publicas:
vote: http://34.67.143.86/
result: http://34.68.66.207/

Nota:
Existe un error en la base de datos al realizar la votacion, el cual indica que se esta 
violando la llave primaria "votes_id_key" de la tabla "votes", segun la revision que se realizo 
tal vez el error se encuentra en la imagen que realiza el regitro de la votacion ya que siempre 
trata de registran votes_id_key=af8024d89fa5828. 
