![Pic 0](images/ex6-0.png)

# Exercise 6 - A Taste of SAP S/4HANA Custom Events

After completing these steps you will have learned about how to create custom events for SAP S/4HANA (and ECC) using the Event Add-On for ERP. On top, you will have consumed one or more events from SAP S/4HANA.

## Exercise 6.1 The Event Add-On for ERP

The Event Add-On for ERP has lately been introduced to further improve event exposure options for SAP's event-driven ecosystem. Consider the Event-Add-On for ERP as a premium and convenience option that comes with a low-code/no-code approach to create sophisticated, clean-core compliant custom events in just a few minutes.

![Pic 1](images/ex6-1.png)

To keep it short let's describe what the Event-Add On is in a few sentences:

- The Event Add-On enables real-time, event-driven, bi-directional communication and batch loads from both SAP S/4HANA and SAP ERP Central Component (SAP ECC) to SAP Integration Suite, advanced event mesh.
- The Add-On is already available via SAP through various commercial models (BTPEA, CPEA, PAYG, Subscription via SAP Store).
- It supports different deployment options of SAP S/4HANA and SAP ECC (including on-premises and SAP S/4HANA, private cloud edition)
- It allows to create custom events in a code-less or alternatively pro-code way and offers extensible payloads
CDS views, classic tables, IDocs can be used for event payload creation
- Comes with templates for selected custom events
- Major parts of the technology have already been in successful use for several years and are now available in an SAP offering specifically tailored for SAP Integration Suite, advanced event mesh
- Scales to enterprise grade numbers of events exposed

Watch a 5 minute demo of the Event Add-On for ERP ![Video 1](videos/IN165_Demo_Event_Add_On.mkv). We will walk you through the creation of a Sales Order event in SAP S/4HANA.

In case you are interested in a detailed demo that you can watch later, find it here: [Devtoberfest 2025 Hands-on session: practical demonstration of the Event Add-On for ERP](https://www.youtube.com/watch?v=vwzqNLISvHo)

## Exercise 6.2 Consume Custom Events form SAP S(4HANA via the Event Add-On

Now that you have seen the event getting created, let us consume it in Advanced Event Mesh.

1. Go back to Advanced Event Mesh and go to the <b>Queue you had created earlier</b>. You can make things easier by searching for your Queue in the search field.

![Pic 1](images/ex6-1b.png)

2. Click on <b>Subscriptions</b>

![Pic 2](images/ex6-2.png)

3. Subscribe for SAP S/4HANA Custom Event Topic by clicking <b>+Subscription</b>, entering the topic for the SAP S/4HANA Custom event and then clicking <b>Create</b>

![Pic 3](images/ex6-3.png)

![Pic 4](images/ex6-4.png)

4. The result should look like below. The queue is now subscribed to the custom S/4HANA event.

![Pic 5](images/ex6-5.png)

5. Click on <b>Messages Queued</b>

![Pic 6](images/ex6-6.png)

6. Now click the <b>Refresh Data</b> button every now and then

![Pic 7](images/ex6-7.png)

You should see that events from the SAP S/4HANA System are getting received and are stored in your queue.

Here you can only see the events coming in. If you want to see the content of the events, you can subscribe the Try me! tool to your queue and consume from there.

7. Go to the Try Me! tool and connect the first the publisher and then the subscriber as you had done earlier

![Pic 7](images/ex6-8.png)

8. On the <b>Subscriber</b> side go to <b>Bind to an endpoint to receive guaranteed messages</b>

9. Select <b>Queue</b>, enter your queue's name and click <b>Start Consume</b>

![Pic 7](images/ex6-9.png)

You should now be able to see the events coming in from the SAP S/4HANA system.

## Summary

You've now explored how to create custom events, listed for them in AEM and store them in a queue for consumption from there.
