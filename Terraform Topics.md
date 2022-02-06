# Topics
1. Basic workflow
2. Providers
3. Resources
4. Variables
5. Datasources
6. State
7. Workspaces
8. Modules
9. Cloud
10. Sentinel
11. State Import
12. Graph
13. Expressions

 ## Terraform workflow
 1. init
 2. validate
 3. plan
 4. apply
 5. destroy

![picture 11](images/21b2c885fa69666fa4dad6127ec4d3a1136591fa6cabee99daccf6877b3b4b09.png)  


## Terraform Language Basics (Configuration syntax)
1. Blocks
2. Arguments
3. Identifiers
4. Comments

### **Terraform Blocks**
![picture 1](images/cfbf25ca681ef62b5eed54e47c0f488c6eecb5a5d9ae41c144869ceb46d845ce.png)  

## Providers
Each resource type is implemented by a provider, which is a plugin for Terraform that offers a collection of resource types. A provider usually provides resources to manage a single cloud or on-premises infrastructure platform. Providers are distributed separately from Terraform itself, but Terraform can automatically install most providers when initializing a working directory.
![picture 2](images/c2ed7322052a0c94b4c06cf8c573e256da71894c9f5b913481de22ac693a90b6.png)  

## Terraform resources
Each resource is associated with a single resource type, which determines the kind of infrastructure object it manages and what arguments and other attributes the resource supports.
![picture 3](images/55a30f10874e17d0a7eafb17754240e65f405d78f347736ac8a4f2586578c1c1.png)  

## Terraform State File
Terraform must store state about your managed infrastructure and configuration. This state is used by Terraform to map real world resources to your configuration, keep track of metadata, and to improve performance for large infrastructures.

This state is stored by default in a local file named "terraform.tfstate", but it can also be stored remotely, which works better in a team environment.
  ![picture 4](images/151d312950c383e8ce48a134e7e27276550b203e94565bcf86e4fd4d6d485357.png)  

## Terraform Remote state File with State Locking

![picture 5](images/8f762f6f123b0434c682b79d17156f586dc5f2d9c51e4c7e4eba10bd8ee1658d.png)  

## Terraform Commands - State Perspective

![picture 6](images/5fc4b4eaa63b4997b088c84cebaa290d3f4f53effdf2f1a92297f02afc6d15cc.png)  

## Type of Provisioners

![picture 7](images/60909cf3861ff21b676144d25c6966c861cd08da9339567d956d92fcabc141c8.png)  

## Terraform Modules

![picture 8](images/ff8ba3336fb88b55be947c91ba8d92fc4bfd6694e0b6da07915c298c03b400a4.png)  

## Terraform workflow

![picture 9](images/1696ad2a33c535400ec165bf3d70af7f7667f1bb5815d53e0075c6609580834a.png)  

## Terraform expression

![picture 10](images/09ad70f3cc6622c748b7526df76225ad5a755c053eb572203ad26e6b81ca965c.png)  


/ <img align="left" width="1000" height="800" src="../../../images/a98e018212947733ebc2020418e36ee9316535f243f0c86339917e1f23e137f0.png">
