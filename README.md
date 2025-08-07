terrform docker project

tools used:
1.playwithdocker
2.terrafom
3.nginx
4.github

steps:
1. install terraform and git o playwith docker instance.
2. create a main.tf configuration file.
3. use these terraform commands to build nginx image.
   -- terraform init
   -- terraform plan
   -- terraform apply --auto-approve
4. run nginx image on 8080 port.
5. destroy docker container
   -- terraform destroy --auto-approve

   screenshots:

   <img width="914" height="325" alt="Screenshot 2025-08-07 113741" src="https://github.com/user-attachments/assets/0ef4ff1e-abfb-4239-9dc5-8e504e5d44b3" />

   <img width="1437" height="394" alt="Screenshot 2025-08-07 113825" src="https://github.com/user-attachments/assets/19dc0225-d35c-4744-8e9c-653f1ae229aa" />

   <img width="1425" height="379" alt="Screenshot 2025-08-07 114254" src="https://github.com/user-attachments/assets/638956aa-9636-465f-ae91-0065feb1b755" />

   <img width="1865" height="688" alt="Screenshot 2025-08-07 114349" src="https://github.com/user-attachments/assets/8fd3a4ce-bff1-4ad5-9f65-7af43254cdd2" />






