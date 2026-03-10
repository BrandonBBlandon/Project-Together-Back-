Diagrama de alto nivel: 
front-> backend general ->db
front -> backend agente ->backend general -> db

componentes del diagrama

Front (Next.js + React): 
-para el front se va a utilizar tailwind( pendiente de aprobacion por saris)
componentes:
--Login
--Admin
--Dashboard
--Inventario
--Ventas
--clientes
--Ajustes
--Conversaciones de agente

Backend: (Node):
middleware:
-auth
-chat de agente
controllers:
-inventory
-sales
-clients
-settings
-chats

DB(MySQL): (pendiente de la imagen)