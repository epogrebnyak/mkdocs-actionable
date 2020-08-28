# Enhancing reliability and resiliency of large-scale IT systems

We offer reliability testing and verification services for companies
operating large-scale IT systems in the financial industry,
e-commerce/retail and other sectors where system uptime is critical,
architectures are complex and release cycles for delivering new user
functionality are accelerating.

At this page, we explain our approach to chaos engineering methodology,
highlight cases where it works best and how reliability testing delivers
value to IT system owners.

### Scope for advanced testing

What kind of company may benefit from  advanced reliability testing? Ideally, it would have at least several of the following attributes:
a high-load system, clear performance expectations, and monitoring and disaster recovery procedures in place:

#### 1. Type of IT system
- A large-scale IT system with a complex architecture, possibly cloud-based
- System downtime or abnormal operation hurts users and is expensive for the company
- Software development team works closely with operations team ("build",  not just "buy")

#### 2. Performance expectations
- Critical user scenarios are prioritized and reflected through meaningful reliability metrics (SLI/SLO)
- The business recognizes the value of system reliability - there is possibly a business-side KPI on reliability
- The company should meet regulatory requirements on reliability

#### 3. Monitoring and disaster recovery
- Monitoring is good enough to reflect parts of hidden system state, but is not noisy
- The team knows how to recover the system after an outage or automated the task
- The incidents are logged and evaluated as they accumulate (postmortems)

Such a system may still have more failures than expected. Technical team and management may want to 
tackle reasons behind incidents and not just handle consequences. Be prepared for upcoming risks, automate recovery, 
not just wait for incidents to happen. By starting reliability testing with chaos 
engineering you move from reactive to proactive strategy in your incident management
and IT system quality assurance.

### Chaos engineering: pioneered by Netflix

Netflix pioneered chaos testing in 2010 upon moving the video streaming
services to the cloud. The actual and designed states of a
cloud microservice-based system diverge. So, rather idealized tests in pre-production
setting provided insufficient guarantees.

Netflix moved to experiment-based testing of a live production system.
They introduced small controlled infrastructure and application faults to learn how a real system reacts to them. 
Does it fail, degrade or self-recover? Embedding artificial failures as a test helped to build a system 
that is more resilient to actual failures.

This testing approach has proven successful and has become a standard
practice in the design and operation of large distributed systems. Chaos
engineering is adopted in retail chains (Walmart),
electronic commerce (Alibaba) and banks (Capital One). Amazon is one of
the largest employers of chaos engineering specialists.

Chaos engineering gains acceptance as it reduces the direct and
hidden costs associated with failures or silent degradations of IT
systems. Simply put, it saves a company money, enhances its reputation
and prevents customer churn. Additionally, it elevates development team confidence 
and lays a path for the company to build and deliver better IT products and services.


### Who can implement chaos testing?

The adopters of chaos engineering are companies where scale meets
complexity: they develop and operate high-load IT systems and aim to
deliver software products to market fast without sacrificing reliability. 
These companies develop their own chaos engineering practice or adopt 
best industry practices.

The demand for chaos testing is growing in response to increased
complexity of IT systems (including microservices architecture and cloud
infrastructure) and faster software product delivery cycle.

There are other reasons that are driving the adoption of chaos testing.
For example, a company may operate multiple systems and services created by
different providers and test for integration errors specifically at the
responsibility boundaries, which traditionally is a hard area for testing 
– full of "not my fault" situations. 

Other common motives include:

- quality improvement for in-house and outsourced software development projects - a company may set a testable reliability requirement that simulates real error-prone operating conditions,
- support and verification of procedures in business continuity, disaster recovery and operational risk management,
- independent audit of IT systems in mergers and acquisitions.

### Our services

#### Core testing service

Our core service is to test client's IT system
using fault injections. It usually takes 21-25 days 
to design and run these tests. The tests are recylced for new releases.

In a typical testing assignment we accomplish the following:

- analyze IT system/service architecture, key user scenarios, and incident history,
- identify failure points, prepare test cases and fault injection scenarios,
- mount software tools for fault injection on a test cluster provided by the client,
- perform the chaos tests and register the results,
- prepare a report describing the testing results and our recommendations.

<!-- The execution cycle for our core testing service is shown in the chart
below. -->

#### Advanced services (test automation, chaos gate, methodology, staff)

In addition to testing individual systems, we also automate and
orchestrate chaos tests. Embeding such tests into release cycle 
creates a systematic quality check (known as "chaos gate").

For companies with enough in-house reliability expertise we can formalize 
a comprehensive corporate chaos testing methodology.

We screen, recruit and train personnel for client's teams involved in chaos engineering.
