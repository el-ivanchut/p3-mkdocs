# Encapsulación de Datos

La encapsulación es el proceso en el que cada capa añade su propia información al enviar datos.

---

## Proceso de encapsulación

1. Aplicación genera datos  
2. Transporte añade puertos  
3. Internet añade IP  
4. Enlace añade MAC  
5. Física transmite bits  

---

## Ejemplo ilustrado

```text
HTTP → Datos
TCP  → Segmento
IP   → Paquete
ETH  → Trama
