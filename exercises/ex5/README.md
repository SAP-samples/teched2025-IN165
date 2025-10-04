![Pic 0](images/ex5-0.png)

# Exercise 5 - The Event-Driven Hockey Stick

After completing these steps you will have learned about how to scale event-driven architecture and why it is also nicknamed as Social Media of the Enterprise.

## Exercise 5.1 Learn about The Event-Driven Hockey Stick

We have today learned some of the basics of event-driven architecture. You have seen some strength that make EDA so powerful:

- loose coupling
- filtering
- buffering
- scale
- publish / subscribe

Typically, initial EDA projects are driven by a specific integration department or a team with technical know how. During these projects EDA know how is built up and the teams learn how to operate EDA environments. Which is different, since a lot of things happen in parallel.

Customers start with a few use cases. Then, driven by a central team, additional use cases are added. The beauty is that you can simply add them to the same infrastructure.

What you really want after having built up EDA know-how is <b>exponential growth</b>: you want the EDA Hockey Stick. Now how do you get there?

That's simple - involve the people that have the business know-how and give them the chance to come up with EDA use cases. The idea is that the different business units can do two things:

1. They can look up available events that they can subscribe to. Based on these events they can build extensions and integrations that are valuable for them. SAP Build would allow business users to do this, in other areas they probably need technical expert guidance and support.
2. They can decide to make events available for others to use. Again, this could either be done by the business or could be done with tech expert support.

![Pic 1](images/ex5-1.png)

## Exercise 5.2 Explore Events in the SAP Business Accelerator Hub

The SAP Business Accelerator Hub documents available SAP standards events. It does so for different SAP cloud applications and on premise backends like SAP S/4HANA Public Cloud Edition, SAP S/4HANA Cloud Private Edition, SAP S/4HANA, SAP Success Factors solutions and plenty of additional SAP applications.

Go to the SAP Business Accelerator Hub by entering the following URL into you browser:

http://hub.sap.com

This will take you to the main page of the Business Accelerator Hub:

![Pic 2](images/ex5-2.png)

Now there are two ways really to look for available events:

1. Either via selecting your SAP <b>product</b> / event source

![Pic 3](images/ex5-3.png)
   
2. Or by clicking on <b>Categories</b> to look for all available events 

![Pic 4](images/ex5-4.png)

We will now take path 1, meaning we will look at available events for SAP S/4HANA Public Cloud Edition.

Go to SAP S/4HANA Cloud Public Edition and click on <b>Events</b>
.
![Pic 5](images/ex5-5.png)

You can now click around and look at available events if you want to. Then enter <b>*salesorder*</b>
 into the search field.
 
![Pic 6](images/ex5-6.png)

Click on SalesOrder events. You get an overview of available SalesOrder events.

![Pic 7](images/ex5-7.png)

Next click on <b>Event References</b>

![Pic 8](images/ex5-8.png)

You can now explore the payload and the header data of available SAP standard events for SalesOrder.

## Exercise 5.3 Experiment with the Event Portal

The Event Portal ...

## Summary

You've now explored how you scale your event-driven architecture.
