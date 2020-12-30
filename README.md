# 195410049_ResponsiCloud
berikut link image php:7.4-apache yang digunakan : 

                          https://hub.docker.com/_/php
                           
                           
Petunjuk : 
1. git clone pada terminal anda : 

                           git clone https://github.com/muhammadsyahrul23/195410049_ResponsiCloud.git
                           
2. pull image dari dockerhub ke terminal anda : 

                            docker pull msyahrul2307/195410049_responsi


3. masuk kedalam direktori file yang diambil dari github : 

                            cd 195410049_ResponsiCloud


4. setelah masuk kedalam direktori 195410049_ResponsiCloud/ jalankan perintah berikut :

                            docker-compose up -d


5. setelah selesai buka web browser anda lalu masuk ke localhost : 

                            localhost --> masuk ke menu web
                            
                            localhost:8080 --> masuk database
 
 6. untuk membuat web bisa melakukan CRUD lakukan setting pada database, Log in ke database : 
 
                            Username : root
                            password : example
                            Database : (kosongkan, jangan di isi)
                            
                            
    lalu create database dengan nama : data                    
    
    buat tabel dengan nama : tb_blog
    
    lalu buat colom : 
    
                    id  | int | length (kosongkan) |  options (koosngkan) | NULL (kosongkan)  | AI (conteng, ini primary key) | sisanya kosongkan
                    
                    nama  | varchar | lenght (25) | options (default) | sisanya kosongkan
                    
                    nim | int | length (9)  | sisanya kosongkan
                    
                    Default values (conteng), Comment (conteng)
                    
                    lalu save.
                    
7. buka lagi localhost, lalu masuk ke menu CRUD. sekarang telah bisa melakukan proses CRUD pada web ini.

8. untuk mematikan docker ketikkan syntax berikut pada terminal : 

                    docker-compose stop
