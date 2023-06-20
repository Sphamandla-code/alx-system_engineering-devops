Postmortem
_______________________________

Headline: Website Outage: What We Learned and How We're Preventing It From Happening Again

Introduction:
----------------

On March 8th, 2023, our website experienced a 1 hour, 20 minute outage. During this time, users were unable to access any pages on the website. We're writing this postmortem to share what we learned from the outage and how we're preventing it from happening again.

Issue Summary:
-------------------

 - Duration: 1 hour, 20 minutes (10:00 AM to 11:20 AM PST)
 - Impact: Our website was down for all users during this time. Users were unable to access any pages on the website.
 - Root Cause: A bug in our load balancer caused it to incorrectly distribute traffic to our web servers. This caused some  of our web servers to become overloaded and unavailable.
 
Timeline:
--------------

10:00 AM: A monitoring alert was triggered indicating that our website was down.
10:05 AM: An engineer investigated the issue and determined that the load balancer was the cause of the outage.
10:10 AM: The engineer took steps to mitigate the issue by disabling the load balancer.
10:20 AM: The website was restored and all users were able to access it again.

Root Cause and Resolution:
----------------------------
The bug in the load balancer was caused by a typo in the configuration file. The typo caused the load balancer to distribute traffic to the web servers in an incorrect manner. This caused some of our web servers to become overloaded and unavailable.
The issue was resolved by fixing the typo in the configuration file. The load balancer was then re-enabled and the website was restored.

Corrective and Preventative Measures:
--------------------------------------
To prevent this issue from happening again, we have implemented the following corrective and preventative measures:
We have implemented a code review process for all configuration changes. This will help to prevent typos and other errors from being introduced into the configuration files.
We have implemented a monitoring system that will alert us if the load balancer is not functioning properly. This will allow us to quickly identify and resolve any issues with the load balancer.

Conclusion:
-------------
We're grateful for your patience during the outage. We're committed to providing a reliable and high-quality experience for our users. We're confident that the measures we've taken will prevent this issue from happening again.

Diagram:
---------
![images](https://github.com/Sphamandla-code/alx-system_engineering-devops/assets/65688263/9f24e71a-4b8f-4f2c-bf06-18269ed72c31)

Humour:
--------
We like to think of this outage as a learning opportunity. We learned a lot about our systems and how to improve them. We also learned a lot about ourselves. We learned that we're a resilient team that can overcome challenges. We're stronger because of this experience.

Call to Action:
---------------
If you have any questions or feedback, please don't hesitate to contact us. We're always looking for ways to improve.

