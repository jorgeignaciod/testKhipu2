# Prueba Técnica Khipu

## Proceso de Integración y Simulación de Pago
Este proceso describe los pasos para integrar y simular un flujo de pago utilizando una cuenta en modo desarrollador, Postman y una página web sencilla.

1. Configuración Inicial en Modo Desarrollador
El primer paso consiste en la creación de una cuenta en modo desarrollador. Esta cuenta proporciona el entorno necesario para realizar pruebas y configuraciones sin afectar transacciones reales.

2. Generación del ID de Pago
Una vez configurada la cuenta de desarrollador, se procede a llamar al endpoint Create payment a través de Postman. Esta acción es fundamental, ya que Postman retorna el payment_id, un identificador único que será crucial para la siguiente fase del proceso.

3. Simulación de la Pasarela de Pago
Posteriormente, en Visual Studio Code, se crea un archivo HTML cuyo propósito es simular una página web. Dentro de este archivo, se agrega el código de integración necesario para mostrar la pasarela de pago. Es en este punto donde se debe insertar el payment_id obtenido previamente. Al incrustar este ID, la pasarela de pago se configura para generar el cobro correspondiente a esa transacción específica.

## Paso a Paso de la prueba

### Obtención payment_id
![Imagen de WhatsApp 2025-05-20 a las 23 11 51_0bd97060](https://github.com/user-attachments/assets/b5b453a1-651a-4998-887d-0d30b13e2b2d)

### Selección de Banco
![Imagen de WhatsApp 2025-05-20 a las 23 12 41_ec351a03](https://github.com/user-attachments/assets/b7740d19-8798-437d-95cb-8cea201b0342)

### Ingresar a mi Banco
![Imagen de WhatsApp 2025-05-20 a las 23 13 01_7793db5e](https://github.com/user-attachments/assets/61613857-0b57-4106-8e59-e182ede08200)

### Selección cuenta origen
![Imagen de WhatsApp 2025-05-20 a las 23 13 14_de27a5f5](https://github.com/user-attachments/assets/7f64747d-9de8-4da5-a60f-4cdf67191cb1)

### Autorización de Pago

![Imagen de WhatsApp 2025-05-20 a las 23 13 38_cad27611](https://github.com/user-attachments/assets/9d4b7366-5296-43c0-855a-a3d14e7cc266)

### Comprobante transferencia

![Imagen de WhatsApp 2025-05-20 a las 23 13 58_88e4af57](https://github.com/user-attachments/assets/1445890d-a2bb-4f66-98da-82d1c61a1f46)
