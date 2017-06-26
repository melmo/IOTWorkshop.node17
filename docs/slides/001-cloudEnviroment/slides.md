# Setting up a cloud environment
+ Basic setup
  + Creating an Ubuntu instance
  + Setting up port permissions
  + getting a static IP
  + sshing in
+ Adding Mosquitto
+ Adding node-red
  + Simple setup
  + Securing it (vital)

---
class: middle, center

# Creating an Ubuntu instance

---

Log in to AWS Management console [here](https://console.aws.amazon.com/console/home)
and browse on over to the Elastic Cloud Compute service
-

<img src="images/image-000.png" width="600">


---

open up the running instances page

<img src="images/image-001.png" width="600">



---

Hit Launch instance

<img src="images/image-002.png" width="600">


---

Select the Ubuntu Server
(Ubuntu Server 16.04 LTS (HVM), SSD Volume Type - ami-835b4efa as of writing)


<img src="images/image-003.png" width="600">


---

Choose the t2.micro (its the only free one) and hit review and launch


<img src="images/image-004.png" width="600">


---

Choose Edit security groups


<img src="images/image-005.png" width="600">


---

Set it up like so


<img src="images/image-006.png" width="600">


---


![](images/image-0.png)


---


![](images/image-0.png)


---


![](images/image-0.png)


---


![](images/image-0.png)


---


![](images/image-0.png)


---


![](images/image-0.png)
