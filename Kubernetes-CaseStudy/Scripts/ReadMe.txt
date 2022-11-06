 #################################################
 Steps followed to  run the application.
 
 1. Deployed MY-SQL  Application
 2. Deployed Customer & Account Service in any Order.
 3. Deployed Angular App by changing appropriate changes.
 4. Ran the application.
 
 Notes : Commands.txt file has been kept for all the individual deployments.
 
 #####################################################
          Implemetation Details:
 #####################################################
 
 1. Angular app has been deployed with loadbalancer service to handle request from the user. This will ensure maximum utilisation of resources.
 2. Auto scaling has been kept for customer and Account micro services by using CPU and Memory Limits for the container. This takes cares of scaling of containers both upscaling and downscaling.
 3. 3 tiers has been isolated by not tightly coupling the connectivity between the tiers.
 4. Credentails has been stored securely by using Secret service.
 5. config and Data has been stored presitently using Volume mounts.
 
