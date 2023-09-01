## FakeSMTP

Este es un servidor local para probar envios de correos con SMTP.

Para ejecutar el servidor se necesita tener java instalado y se lo activa con el siguiente comando:


```bash
java -jar fakeSMTP-2.0.jar -s -b -p 2525 -a 127.0.0.1
```

- (-s) Ejecutar el servidor automaticamente.
- (-b) Esconder la GUI de la aplicación
- (-p) Puerto que usara el servidor de correos
- (-a) Direcciones que se aceptan para permitir la comunicación

### **Créditos**

El código original puede encontrarse en su repositorio oficial en [FakeSMTP](http://nilhcem.com/FakeSMTP).
