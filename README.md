https://www.digitalocean.com/community/tutorials/how-to-use-the-digitalocean-api-v2-with-ansible-2-0-on-ubuntu-14-04

* Put DigitalOcean API token in environment variable DO_API_TOKEN!

* Activate virtualenv with Ansible installed!

Get a list of all available images in the DigitalOcean v2 API:

`curl -X GET --silent "https://api.digitalocean.com/v2/images?per_page=999" -H "Authorization: Bearer $DO_API_TOKEN"` 

