Trabajo Final 

Se versionaron los manifiestos y las imágenes que se utilizaron para el despliegue del trabajo final. Se utilizó google cloud para desplegar las aplicaciones y la exposición de las aplicaciones están en las siguientes ips públicas: 

vote: http://34.67.143.86/ result: http://34.68.66.207/

Nota: Existe un error en la base de datos al realizar la votación, el cual indica que se está violando la llave primaria "votes_id_key" de la tabla "votes", segun la revision que se realizo tal vez el error se encuentra en la imagen que realiza el registro de la votación ya que siempre trata de registrar votes_id_key=af8024d89fa5828.
