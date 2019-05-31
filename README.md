```
 __          __  _        _____                    _           
 \ \        / / | |      / ____|                  | |          
  \ \  /\  / /__| |__   | |     _ __ __ ___      _| | ___ _ __ 
   \ \/  \/ / _ \ '_ \  | |    | '__/ _` \ \ /\ / / |/ _ \ '__|
    \  /\  /  __/ |_) | | |____| | | (_| |\ V  V /| |  __/ |   
     \/  \/ \___|_.__/   \_____|_|  \__,_| \_/\_/ |_|\___|_|   
                                                               
                                                               
```
#### Hedef web sitesini tarayarak linklerini listeleyen bir web crawler scripti || A web crawler script that lists links by scanning the target website.


#### Kurulacak modül

* Linux için kurulum
```
sudo pip install -r requirements.txt
```

* Windows için kurulum
```
python -m pip install -r .\requirements.txt
```

#### Kullanım

* Örnek Kullanım1
```
python spider.py --url http://10.0.2.6/mutillidae
```

* Örnek Kullanım2
```
python spider.py -u http://10.0.2.6/mutillidae
```

![spider](https://user-images.githubusercontent.com/25087769/58699291-cf2a2900-83a5-11e9-8a8e-6cd237c5ffac.PNG)
