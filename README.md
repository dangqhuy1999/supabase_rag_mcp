# supabase_rag_mcp
test

Build `supabase` with docker follow [Guide Sefl-host supabase](https://supabase.com/docs/guides/self-hosting/docker#accessing-supabase-studio)

## Note: 
  
  Before you run `docker compose up -d` , you should ensure any port related is closed
  
  If a service is running on specificed port related to list service of supabase :

  Turn off that service:

  `sudo lsof -i :5432` # pre check 

  `sudo systemctl stop postgresql` # stop service 

  `sudo systemctl disable postgresql` # disable service 

  `sudo pkill -u postgres` # additional pkill service

  `sudo lsof -i :5432` # valid check 

##

   
