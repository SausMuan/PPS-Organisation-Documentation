# Project process


This chapter describe the process of the project. That mean how the project will be executed.

```plantuml

@startuml Process diagram

start
:start martijn;
:Start;
:Get to know eachother;
:Dive in to the assignment;
:Give each team member a role;
:Plan a meeting with client;
:Get to know the client;
:Ask client to tell something about the assignment;
fork
repeat
:Write down unclear points;
:Update progress of project to client;
:Aks client to clearafy unclear points;
repeat while (unclear points?) 
fork again
:Write requirements in ADR;
:Divide system in subsystems;
:Make diagram of the subsystems;
:Divide subsystems among team members;
:Hold meetings to make sure that interface are clear for members;
:Combine solutions of subsystems;
:Order components;
:Build system;
:Test system;
endfork
:Write down results and recommendations;

@enduml

