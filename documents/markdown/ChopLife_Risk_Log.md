# ChopLife Risk Log & Risk Register

ChopLife App — Food Delivery Platform for the African Market

Project Manager: Morenikeji  |  Sponsor: Mr. Micah Timileyin  |  Version 1.0  |  June 2026  |  Women Techsters Bootcamp Cohort 5.1

This Risk Log identifies, assesses, and documents all known project risks for the ChopLife App. Each risk is assigned a likelihood rating, impact rating, and an overall risk score. Mitigation strategies and risk owners are clearly defined to ensure the team can respond proactively before risks become issues.


## Risk Rating Scale

| Rating | Likelihood / Impact | Risk Score | Description |
|---|---|---|---|
| High | Likely to occur | Critical — Act immediately | Has a strong chance of occurring and/or would cause significant disruption to the project if it does |
| Medium | Could occur | Monitor closely | May occur under certain conditions and would cause moderate impact on the timeline, budget, or quality |
| Low | Unlikely to occur | Low priority | Unlikely to occur and would have minimal disruption even if it does. Continue monitoring. |


## Risk Register

| ID | Risk Description | Category | Likelihood | Impact | Score | Mitigation Strategy | Owner | Status |
|---|---|---|---|---|---|---|---|---|
| R-01 | Payment gateway integration delays | Technical | High | High | High | • Initiate API access requests with Paystack and Flutterwave in Phase 1<br>• Identify and pre-qualify two backup payment providers<br>• Allocate 2 weeks of buffer time in the payment sprint<br>• Assign a dedicated integration engineer to manage provider relationships | Dev Lead | Open |
| R-02 | Low vendor adoption at launch | Business | Medium | High | High | • Begin vendor outreach and education campaign 3 months before launch<br>• Offer zero commission for the first 3 months to incentivise early sign-ups<br>• Assign dedicated vendor relations officers in each country office<br>• Create simple onboarding materials in local languages | Country Mgrs | Open |
| R-03 | App Store / Play Store rejection | Technical | Low | High | Medium | • Conduct a thorough pre-submission review against Apple and Google policies<br>• Allocate 4 weeks for the review process to avoid timeline pressure<br>• Engage a mobile compliance consultant to review the app before submission<br>• Prepare detailed responses for potential rejection reasons in advance | IT Support | Open |
| R-04 | Regulatory delays in Nigeria, Ghana, or Cameroon | Compliance | Medium | Medium | Medium | • Engage local legal counsel in each country from Month 1 of the project<br>• Begin business registration processes in all three countries simultaneously<br>• Build a 4-week regulatory buffer into the Phase 5 launch plan<br>• Maintain regular contact with regulatory bodies throughout the project | HR/Legal Lead | Open |
| R-05 | Team capacity constraints | Resource | High | Medium | High | • Establish clear sprint workload limits — no team member carries more than 3 active tasks<br>• Hold weekly capacity check-ins to identify and resolve overloading early<br>• Identify freelance developers as backup resources for peak sprint periods<br>• Project Manager to escalate resource conflicts to sponsor within 48 hours | Project Mgr | Open |
| R-06 | Competitor product launch during development | Market | Medium | Medium | Medium | • Accelerate MVP delivery of the top 3 differentiating features (AI suggestions, group order, bill split)<br>• Conduct quarterly competitor analysis reviews and adjust roadmap if needed<br>• Strengthen vendor and rider relationships early to lock in supply-side partnerships<br>• Focus marketing on ChopLife's unique African-market positioning | Product Owner | Open |
| R-07 | Poor internet connectivity affecting app performance | Technical | High | Medium | High | • Design app for low-bandwidth environments from the start (lazy loading, offline mode)<br>• Compress all images and implement efficient API data structures<br>• Test app performance on 3G networks during QA phase<br>• Provide a lightweight version of the app for low-connectivity zones | Dev Lead | Open |
| R-08 | Payment fraud and security breaches | Security | Medium | High | High | • Implement end-to-end encryption for all payment transactions<br>• Conduct penetration testing before launch<br>• Integrate fraud detection tools with payment providers<br>• Establish an incident response plan and communicate it to the team | IT Support | Open |
| R-09 | Rider shortage in launch cities | Operations | Medium | High | High | • Begin rider recruitment 2 months before launch in each city<br>• Partner with existing moto-logistics companies for initial rider supply<br>• Offer sign-on bonuses and guaranteed minimum earnings for early riders<br>• Monitor rider-to-order ratio daily and trigger recruitment campaigns if ratio drops | Country Mgrs | Open |
| R-10 | Budget overrun beyond \$74,000 USD | Financial | Low | High | Medium | • Track all expenditure weekly against the approved budget in Jira<br>• Enforce a 10% contingency reserve and require sponsor approval before spending it<br>• Conduct monthly budget reviews with the sponsor<br>• Identify and defer non-critical features to Phase 2 if cost pressures arise | Project Mgr | Open |
| R-11 | Scope creep — unplanned features added mid-project | Scope | High | Medium | High | • All new feature requests must go through a formal change request process<br>• Product Owner has authority to reject requests that are out of scope<br>• Review and rebaseline scope at the end of each sprint<br>• Any approved scope changes must be accompanied by a budget and timeline impact assessment | Product Owner | Open |
| R-12 | Key team member unavailability | Resource | Medium | High | High | • Document all technical decisions and processes so knowledge is not siloed<br>• Cross-train at least one backup person for each critical role<br>• Maintain a skills matrix to quickly identify who can cover which tasks<br>• Establish an escalation path to the sponsor if a critical resource is lost | Project Mgr | Open |


## Risk Summary

| Total Risks | High Risk | Medium Risk | Low Risk |
|---|---|---|---|
| 12 | 7 | 3 | 2 |

— End of Risk Log —

Women Techsters Bootcamp Cohort 5.1  |  Technical Project Management  |  Group 5  |  ChopLife App v1.0
