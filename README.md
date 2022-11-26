# AONOG2022-SMOKEPING Presentation

## How to Use

### Clone repository to your localhost

git clone https://github.com/schumacherneto/AONOG2022-SMOKEPING.git

### Docker-compose pull smokeping image and build a container *aonog2022-smokeping*

 ```
 docker-compose up -d
  ```


### Execute docker container

  ```
 docker exec -it aonog2022-smokeping bash
  ```

## Structure
.
├── README.md
├── config
│   ├── Targets
│   ├── config
│   └── data
├── data
└── docker-compose.yml

Note: Edit Targets file in order to modify desired destinations


### Docker-compose "stop" in order to preserve the container or "down" to remove container 

 ```
 docker-compose stop 

or

 docker-compose down
  ```

