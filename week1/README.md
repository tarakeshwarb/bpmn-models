This repository contains BPMN models for three real-world processes. Each process is modeled using basic BPMN elements such as Start Events, Tasks, Exclusive Gateways, and End Events.

Scenario 1 – Employee Leave Approval

The process starts when an employee submits a leave request. The HR system checks the available leave balance. If sufficient leave is available, the request is sent to the manager for approval. Based on the manager's decision, the system either updates the leave balance and sends an approval notification or sends a rejection notification. If there is not enough leave balance, the employee is notified and the process ends.

Main BPMN elements: Start Event, Service Tasks, User Task, Exclusive Gateways, End Events.


Scenario 2 – Online Purchase Order Processing

The process begins when a customer places an order. The system checks product availability and then processes the payment if the product is available. An unavailable product or failed payment leads to a notification and process termination. If payment succeeds, the order is confirmed, the product is prepared and shipped, and the customer receives a shipping confirmation.

Main BPMN elements: Start Event, Service Tasks, Manual Tasks, Exclusive Gateways, End Events.


Scenario 3 – IT Service Request

The process starts when an employee submits an IT support request. The help desk registers the request and checks its severity. Depending on the severity, it is assigned to either a support technician or a senior technician. The problem is then investigated. If it can be resolved internally, it is fixed; otherwise, it is escalated to an external service provider. After resolution, the request status is updated and the employee is notified.

Main BPMN elements: Start Event, User Tasks, Exclusive Gateways, Alternative Paths, End Event.


BPMN Concepts Used
Start Event – shows where the process begins.
Tasks – represent activities performed by a person or system.
Exclusive Gateway – represents a decision between different paths.
Sequence Flow – shows the order of activities.
End Event – shows where a process path finishes