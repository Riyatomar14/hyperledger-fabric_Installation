# hyperledger-fabric_Installation

# Prerequisites

1. cURL — latest version
 
2. Docker — version 17.06.2-ce or greater

3. Docker Compose — version 1.14.0 or greater

4. Golang — version 1.11.x

5. Nodejs — version 8.x (other versions are not in support yet)

6. NPM — version 5.x

7. Python 2.7

 * A) Add the new user “fabric”
   
```
sudo adduser fabric
```

* B) Add the user “fabric” to the Sudo groups

```
sudo usermod -aG sudo fabric
```

* C) Login to “fabric” user

```
su fabric
```

* D) Test the sudo access

```
sudo ls
```

* E) check your curl , docker, docker-compose , go , python , npm , nodejs version
  
![image](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/b7128a19-9177-485b-b8fa-f56d89a13411)

![Screenshot 2024-04-29 201234](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/fefbdb3c-6697-455f-b51b-69a39191a30f)

![image](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/75b1cdd2-28b2-4994-9a64-002ae7a4b6e9)

![image](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/5e11a98c-e728-4212-91af-c71f625ff450)

![image](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/f695d81d-6e23-4a1a-997d-a6f17f68f54b)

![image](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/470f9b01-2ba6-449f-a856-b5b7a7d7b17c)

# Install Samples, Binaries and Docker Images

* A) Make the directory where you want to install the fabric-samples

```
mkdir Riya(in my case)
cd Riya
```

* B) Determine the directory where you want to download the fabric samples. Open the directory in terminal and run the below command.

```
curl -sSL http://bit.ly/2ysbOFE | bash -s
```

![image](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/fe9317f8-e371-47d7-aef2-0b2634937f81)

![image](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/f5ec76d3-6acc-4707-88bd-1e97bd14a63f)

* C) Open the fabric-samples and go to the first-network.

```
cd fabric-samples/first-network
```

![image](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/4737db60-f792-402e-8ad6-7b33aa2cf65d)

![image](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/2bba1dd0-7770-48a6-9c10-d6bb4d67da0f)


* D) To test it, run the ```network.sh``` . It is a test script, it first set up the network with 2 organizations org1 and org2 with 2 peers each and an orderer .


```
./network.sh up
```


![Screenshot 2024-04-29 215224](https://github.com/Riyatomar14/coding-in-advance-c/assets/143107173/c8660b4f-2e2c-44d3-bc83-7e40898aaa97)


