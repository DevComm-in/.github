# DevComm


```java

DevComm mDevComm = new DevComm();

System.out.println("About DevComm");
mDevComm.introduceYourself();

System.out.println("\n\nOur Services");
mDevComm.whatCanYouDo();

System.out.println("Our Products");
mDevComm.listYourProducts();

System.out.println("Our Team");
List<Member> team = mDevComm.getTeamMembers();
while(team.hasMember()){
   System.out.println(team.nextMember());
}

```



```bash

About Devcomm
DevComm is ...


Our Services
DevComm provides ...


Our Products
1. ...
2. ...
3. ...


Our Team
1. Sachin Kumar
2. Subhash Panndey

```
