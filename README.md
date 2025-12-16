# Agustín Borreguero Castro, José Antonio Jiménez Bernaza
## ¿Qué ocurre con el Cliente 2? 
Cuando arrancamos el Cliente 2 no puede conectarse ni le deja mandar ningún mensaje porque el servidor está durmiendo debido al Thread.sleep(15000).
## ¿Por qué no puede ni siquiera enviar su mensaje? 
No puede mandar ningún mensaje el Cliente 2 porque el servidor solo tiene un hilo principal, por lo que el hilo está ocupado con el Cliente 1 y no puede acepar nuevas conexiones, 
por lo que el Cliente 2 solo podrá hablar con el servidor cuando acabe con el Cliente1.
## Captura de pantalla demostrando la Fase 3
<img width="1365" height="561" alt="image" src="https://github.com/user-attachments/assets/50a3b1b4-b821-4510-b028-4ff5df6072df" />
