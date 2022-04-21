# pihole-docker-compose
normal version(without root)
  - description: 
    - environment
      - WEBPASSWORD: 'admin'
  - file: docker-compose.yml

advanced version(without root)
  - description
    - enrivionment  
      - WEBPASSWORD: 'admin'
      - DNSMASQ_USER: 'root'
  - file: docker-compose(root).yml

