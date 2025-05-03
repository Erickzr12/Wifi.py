Medición de velocidad de Internet: Mide la velocidad de descarga y subida usando el módulo speedtest-cli y muestra los resultados en la interfaz. Si la velocidad de descarga es inferior a 5 Mbps, se envía una notificación.

Escaneo de redes Wi-Fi: Escanea redes disponibles usando netsh en Windows o nmcli en Linux y muestra los resultados en un área de texto.

Obtención de dispositivos conectados: Muestra los dispositivos conectados a la red utilizando arp -a en Windows o nmap en Linux.

Gráfico en tiempo real de la velocidad de Internet: Muestra un gráfico en tiempo real de la velocidad de descarga y subida cada 30 segundos utilizando matplotlib.

Notificaciones: Notifica al usuario si la velocidad de descarga es baja y permite enviar notificaciones personalizadas mediante el módulo plyer.

Programación de pruebas periódicas: Usa la biblioteca schedule para ejecutar pruebas de velocidad cada 10 minutos de forma automática.

Reporte en CSV: Guarda los resultados de las pruebas de velocidad en un archivo CSV.

Reportes en PDF: Permite guardar un reporte básico de la red en formato PDF usando FPDF.

Otras funcionalidades: Incluye opciones como liberar y renovar la IP, obtener información sobre la latencia del proveedor de Internet, escaneo de vulnerabilidades básicas y visualizar el historial de dispositivos conectados.

Para usar este código, asegúrate de tener instalados los siguientes módulos:
speedtest-cli

plyer

matplotlib

fpdf

schedule
