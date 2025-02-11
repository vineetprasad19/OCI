# OCI
Complete Oracle Cloud Infrastructure (OCI) notes

![image](https://github.com/user-attachments/assets/3173c0d0-31cf-4ee8-9aab-5a59fd16a8d9)  
![image](https://github.com/user-attachments/assets/f537de63-71c1-4d17-8199-9cb456c4dba6)

Let's summarize what we learned in this lesson. So we looked at region. Region comprises of availability domains. Availability domains comprise of fault domains. So let's look at the inside-out view. So first let's start with fault domain. Fault domain provide protection against failure within an availability domain. Availability domain themselves provide protection from entire availability domain failures, particularly in a multi-AD region.  
And then you have this concept of region pair where in every country we operate on, most of the countries we operate, we have at least two data centers. So you could use the second data center for disaster recovery or backup, or it also helps you with to comply with data residency and compliance requirements. And then not only this, we also have SLAs on availability, management, and performance.  
To recap, we looked at the physical architecture of OCI with regions, which are geolocations. We looked at availability domains. And then every availability domain has three fault domains. So use these architectural constructs to design your applications which are highly available and avoid single points of failure Thanks for watching.  
  
![image](https://github.com/user-attachments/assets/9106de8b-8f60-43fe-8054-0f458285ab65)  
![image](https://github.com/user-attachments/assets/564007f5-f498-4db0-b0b6-7911ef564e1e)  
![image](https://github.com/user-attachments/assets/240656df-a852-47e8-936f-0391a5d37f01)  
  
So in a nutshell, that's our distributed cloud story. There are three main advantages of using Distributed Cloud. First is you can deploy services where you need to or how you need to. So that's number one. Number two is you get the same platform, pricing, and experience across whether you are running in the public cloud, dedicated cloud, hybrid cloud, or multicloud.  
And then that's the second and then the third is you can address regulatory and sovereignty needs through offerings such as Dedicated Region and some of our hybrid services.  

![image](https://github.com/user-attachments/assets/a3280f86-3c36-4b85-b522-00555e25e0ce)
![image](https://github.com/user-attachments/assets/db6d47e2-eef8-44a2-a0c9-4861ff499216)
![image](https://github.com/user-attachments/assets/66da8578-2e7b-4c1d-b7e1-5260e378bcf5)
![image](https://github.com/user-attachments/assets/8ca55547-a998-43ed-86b6-d500a66a134f)
![image](https://github.com/user-attachments/assets/09776935-f204-4960-b817-69a0c12b7012)

![image](https://github.com/user-attachments/assets/48687d10-3c61-49b3-9b81-aa1a2109db70)
To wrap up, we looked at how you do authentication in OCI, the three mechanisms, user name, passwords, APIs signing keys, authentication tokens. And then we looked at how you do authorization in OCI through policies. Policies are really powerful. They are very easy to understand, human readable. But at the same time, they give you a lot of advanced capabilities to implement really fine-grained access control.   

![image](https://github.com/user-attachments/assets/d8bb2de1-dbae-43e0-b4e7-8b3c37ea8738)
![image](https://github.com/user-attachments/assets/e65ab5a0-9fa8-48a8-bad1-98aefdd5e109)
![image](https://github.com/user-attachments/assets/67ac9353-c182-44e8-89fd-07772b43764a)

![image](https://github.com/user-attachments/assets/005d3ae1-0060-4d01-85a2-7ed5d3855004)
![image](https://github.com/user-attachments/assets/4536bd7b-b247-462e-9247-c4a541e660b3)
![image](https://github.com/user-attachments/assets/a84b8344-a5ac-40ce-85e3-acf114ae9c03)
![image](https://github.com/user-attachments/assets/2b693ded-b3d9-4396-88fd-7827467f700e)
![image](https://github.com/user-attachments/assets/ae7a35a4-bbda-4e9e-b513-57a5e37aa61d)

![image](https://github.com/user-attachments/assets/69493891-3c8d-4f17-a77b-a0ae06516d8f)
![image](https://github.com/user-attachments/assets/61be9781-a20b-4516-9af5-88a5aa2e6503)
![image](https://github.com/user-attachments/assets/fd973253-ee02-4109-9cdc-9255a0652a05)
![image](https://github.com/user-attachments/assets/e73086c5-6c63-4ed1-a53b-475133c6f46c)
![image](https://github.com/user-attachments/assets/6fe5dc17-2c72-435d-8c13-4da26fdad563)
![image](https://github.com/user-attachments/assets/a2a185f2-7476-4067-b914-0a91f247ff78)
![image](https://github.com/user-attachments/assets/d14a9054-297f-475c-a615-d5ac91e0437a)

![image](https://github.com/user-attachments/assets/0bd34a10-6245-4b87-a27a-e42f1752ee9a)
![image](https://github.com/user-attachments/assets/15d9b751-5519-4fa5-b576-199c09dc04e0)
![image](https://github.com/user-attachments/assets/02c1877c-6f2d-4bb3-987a-daebd4c6d1ce)
![image](https://github.com/user-attachments/assets/26e6c99b-81a4-4f30-892f-66bc7700dc47)
![image](https://github.com/user-attachments/assets/0d1c23ba-cbb7-4291-a157-22834d6c8ee0)

![image](https://github.com/user-attachments/assets/f6a9dbc7-4b5b-4ef0-a4be-6206c5be7cd5)
![image](https://github.com/user-attachments/assets/02234d14-181c-444c-9151-1486bbff613a)
![image](https://github.com/user-attachments/assets/0d0d5d25-d7ed-426b-99bb-98821dbdc48e)
![image](https://github.com/user-attachments/assets/70a4a309-9da5-4ec6-87be-ceb600f703f1)
![image](https://github.com/user-attachments/assets/a10a00fb-cf74-4434-aa68-ed3e41d7386d)

![image](https://github.com/user-attachments/assets/6d879690-e59a-407d-bc2a-c227b3df347c)
![image](https://github.com/user-attachments/assets/0516c507-7d98-4648-b982-a838ab845403)
![image](https://github.com/user-attachments/assets/c1cb262b-5991-40ef-9f27-060abce0c204)
![image](https://github.com/user-attachments/assets/8f183c7f-742a-497b-8fc6-ba659166a4a0)
![image](https://github.com/user-attachments/assets/54e2e5c9-345a-4a83-a5fb-acf03697b495)
![image](https://github.com/user-attachments/assets/8ad29373-7eef-4688-b2d3-314119752fe2)
![image](https://github.com/user-attachments/assets/68ce7bcf-3474-45bd-aa69-c0e3e26f767f)







