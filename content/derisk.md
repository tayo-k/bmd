# De-risking

##### TL;DR: 
Focus on building fault tolerance into the people, product and processes

The engineering organization must be able to clearly outline – in the grid or elsewhere – the specific ingredients that are relevant to mitigating risk along the journey from conception, to delivery of a product. 

It’s important to clarify here that we’re not talking about fixation on bug-free software, hardware or services. Bugs will be introduced. Failures will happen. Timelines and the business landscape will change. 

What makes all the difference is having guardrails installed that will help the organization 

- Quickly detect defects 
- Adjust to shifting business and technical landscapes
- Minimize scope of probable damage by security or other risk factors 

These guardrails will serve to either help prevent the addition of risk factors to the engineering journey, or quickly detect the presence of these risk factors so that all that remains is a question of how the risk factor will be addressed.

By defining and categorizing the observable ingredients dedicated to de-risking the engineering journey, we can track and measure the status and risk profile of the “Build” guardrail of an engineering culture. 

On the strengths of prioritizing De-risking, an engineering organization can more confidently experiment, rapidly prototype and innovate. We arrive at a more fault-tolerant delivery and operational support of a software product. 

### Automation in de-risking
Automation is the single most powerful tool in the pursuit of mitigating risk in the course of engineering. The effective engineering culture prioritizes automating - wherever practical - the following items:

- Testing (unit, integration, end-to-end, performance, functional etc)
- Security
- Performance Monitoring
- Code quality checking
- Operations (deployment, approvals etc)

A culture that prioritizes automation all along the engineering process can afford to experiment more and drive innovation. 

A BMD grid as devised by engineers could look like the following

|           | Planning                           | Development                                                         | Pre-push                                   | Pre-merge                                                                                            | Post-merge             | <add-more> |
|-----------|------------------------------------|---------------------------------------------------------------------|--------------------------------------------|------------------------------------------------------------------------------------------------------|------------------------|------------|
| People    | `Product Owner`<br><br>`Team Lead` | `Product Owner`                                                     |                                            |                                                                                                      |                        |            |
| Processes | `Sprint Planning`                  | `Product Owner Demo`<br><br>`Design Review`<br><br>`Deploy alerts`  |                                            | `Run Integration Tests`<br><br>`Microbenchmarks`<br><br>`Sacrifice a chicken`<br><br>`Pray it works` |                        |            |
| Tools     | `Planning Checklist`               | `Integration Tests`<br><br>`In-IDE linter`<br><br>`Static Analyzer` | `Linter Githook`<br><br>`Security Scanner` | `Security Scanner`<br><br>`Static code analyzer`                                                     | `Docker image scanner` |            |

## Delivery Reliability Engineering
Delivery Reliability Engineering (DRE) is the practice of 
- Being able to distinctly identify risk factors to the predictable delivery of a software product throughout its lifecycle.
- Being able to define mitigation tactics and strategies to address risk factors at specific stages of the engineering process

Where Site Reliability Engineering (SRE) is focused on mitigating risk to the software product (mostly after it’s been built and deployed); DRE will include managing risk - technical and non-technical - while the product is under development. 

It will also cover factors such as:  
- Process breakdowns and missing dependencies. 
- Having the right conversations with partners at the right time
- Shifting tests left, and automating them
- Aligning on expectations with partners early
- Defining and enforcing quality and security gates at specific junctures of the engineering process. 
- Introducing monitoring, tracing and alerting pre-production to catch defects in transit
- Building in buffer in timelines for deliverables, to account for sundry unforeseen circumstances
- Mitigating scope creep

This is the very essence of de-risking a product. Guardrailing the delivery of the final product sets the foundation for more aggressive innovation and on-time (or near-time) delivery. As a practice, DRE encompasses both the human and technical aspects of product delivery. It’s also an ongoing process that the entire engineering organization should be invested in. An individual or group tasked with DRE could draw up a grid that looks like so:

|           | Discovery | Pre-planning | Planning | Development | Quality Assurance | Deployment |
|-----------|-----------|--------------|----------|-------------|-------------------|------------|
| **People**    |           |              |          |             |                   |            |
| **Processes** |           |              |          |             |                   |            |
| **Tools**     |           |              |          |             |                   |            |

This should be used to answer the question “What are you doing to safeguard the timely delivery of a quality product?”. 

This representation will allow the individuals responsible for timely and qualitative delivery to clearly map out the ingredients and timing involved.
Another advantage is that this yields a reusable template for delivering similar types of features and projects

