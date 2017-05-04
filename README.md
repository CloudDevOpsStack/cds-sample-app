This is the Hello-World App based on Python.

Run this app by following commands,

	docker build -t <Image-name> .
	
	docker create --name <Container-Name> -p <Exposed_Port>:<Internal-Port> <Image-name> 
	
	docker start <Container-Name>
	
	Docker ps 
