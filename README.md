# SOC-in-a-Box
### Bringing together open source Security tools in a plug-and-play Security Operations Center
Many cloud based software companies are looking for a better solution to their [Security Operations Center (SOC)](#what-is-a-security-operations-center) needs than the expensive black box solutions currently available.

SOC-in-a-Box provides an open source solution allowing you to see exactly what is being done and have complete visibility into the software being used to protect you. In addition, being open source means there is no cost to you! Just follow the easy instructions included for those with a basic technical background. A subscription service model will be added soon to provide for those who would like a truly plug-and-play experience. We'll take care of setting things up, keeping them running, and providing additional support.

SOC-in-a-Box is the perfect solution when solid security, cost, and transparency are important.

## Summary
SOC-in-a-Box is the tool of tools aimed at integrating the most effective security tools and providing a simple plug-and-play SOC. Many tools have been developed to fill various needs and categories of incident response, from management of events to the detection and/or prevention of certain types of security events. Integrating all these tools can be a time-intensive challenge. We aim to bring these tools together for you.

### What is a Security Operations Center?
A Security Operations Center (SOC) is typically a team of professional Security Engineers that monitors, detects, and responds to malicious activity against a business. A SOC protects a company and its customers' data. Automated tools are increasingly being used to perform and/or augment much of the work a team of engineers would do.

### Why do I need a SOC?
Just in 2020, malware usage increased 358% and ransomware by 435% compared to the previous year, and malicious activity saw an increase of 653% compared to the same month of July in 2019 based on a study by [Deep Instinct](https://www.helpnetsecurity.com/2021/02/17/malware-2020/). [RiskIQ reasearch](https://www.riskiq.com/resources/infographic/evil-internet-minute-2019/) found that cyber crime is resulting in a cost of $2.9 million every minute! [IBM research](https://www.ibm.com/security/digital-assets/cost-data-breach-report/#/)  found that the average attack costs $3.86 million! Cyber protection is no longer a nice-to-have. To operate in the modern, technological age, cyber security is a critical component to protecting yourself and your customers.

### What makes SOC-in-a-Box different?
SOC-in-a-Box finds and integrates the open source tools that best fit the recommendations and requirements specified in leading security frameworks for you. These automated tools then run and notify you of security threats. All of this is put together in one easy to start package!

### Who is this for?
Small businesses make up 99.9% of all U.S. businesses! With a significant amount of those being online, cyber security is a critical consideration to ensure your business and customers stay safe. SOC-in-a-Box helps to make sure you have the security you need without necessarily having all the technical expertise or expense another solution would require.

### How do I start?
Follow our simple quickstart instructions [here](quickstart.md)

## Diagram
![SOC-in-the-Box Diagram](https://lucid.app/publicSegments/view/f787dc13-5b52-42b4-a642-0e5dd69be8c1/image.png)
### Explanation
SOC-in-the-Box is built with extensibility in mind. We can take log events and do the analysis for you based on the latest threat detection insights. But we can also ingest any other alert you throw at us via our Security Event API. These can come from any source you'd like to set up. These are then turned into Security Events, which are sent to the Security Event Hub. Security Events are stored in the Security Event Database. They are also pulled into Security Event Processing, which looks through the Event for different attributes. When a given attribute is found, it triggers a service built for that kind of trigger to collect additional investigation information. At the same time, the Security Even is sent to the Event Correlation service. This service queries the database for correlated events based on correlation rules that are constantly being updated. This all plays into the processing. SOC-in-the-Box will do the work for you in many cases. It will keep you up to date with notifications about the event, information gathered, and actions taken. Anything it can't determine itself, it will send to you, and request input or simply provide all the information you need to act.

## On the Roadmap
- Identify the most effective open source tools evaluated against leading security frameworks
  - Prioritize integration of identified tools 
- Introduce Terraform configuration files with integrated tools as they are added to SOC-in-a-Box
- Fill in [Quickstart](quickstart.md) instructions
- Build out documentation
- Create a tiered service model. 
  - #### Tier 1
    A self-service tier that will always be free including access to our open source solution and documentation
  - #### Tier 2
    A subscription that includes our setup of SOC-in-a-Box in your cloud environment with access to support
  - #### Tier 3
    A subscription including Tier 2 plus requests for planning our integration path into the future 
    - What priority should we have for future integration with which tools? 
    - Early access to new integrations

Have suggestions? Please reach out via [email](mailto:socinabox@pm.me)
