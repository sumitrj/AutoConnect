# AutoConnect-Failure-detection-for-Automobiles

## Note to readers
The version of the project showcased here is an abstract version of the real product but highlights the origin and thought process of the product.

<b> IPR 
This project has been presented at multiple platforms and has been endorsed by IET On Campus - VIT. The product is protected by IPR laws.
The purpose of this repository is to help readers gain technical insights over various domains of technology that intersected here and NOT to be considered as free for development at personal level.
</b>

The technical details of project can be found at https://github.com/vivanks/AutoConnect-IoT-Failure-Prediction. Project is completed with Vivank Sharma, the owner and fellow collaborator of the mentioned repository.


## Problems Considered:
Most cases of machine failures are due to negligence of the owner about their machines. In most cases, the owner is unaware of the fault diagnostic methods or finds it to be a tedious task. It's only when a mechanic checks the machine, that the issues at brought to knowledge of service stations.

Service stations generally don't have the knowledge of conditions of the vehicles near them.

This poses a need of alert systems which get triggered when a machine's health parameters are in certain intervals.

## Proposed Solution:
All the systems should be embedded with sensors such that all crucial data of systems of automobile  is being uploaded to a database on cloud which is accessible by the owner and service centre. This would enable the service centre to analyse which vehicles need repairs and schedule appointments accordingly. 

## Goals:
### Sensors for different systems of automobile: 
Since most owners are unable to check crucial parameters of systems, sensors need to be integrated with the systems such that the data can be obtained on a common platform/cloud.

### Fault Detection Algorithm: 
Algorithms need to be made to identify if any system of a certain vehicle is faulty and how faulty it is. Accordingly, the prescribed time of getting repairs/updates will be updated on the database.
