# Emergency Playbook
_Starter Template made available through "Looks Good To Me: Constructive Code Reviews" by Adrienne Braganza_. 

_To help your team get started with an Emergency Playbook, I’ve provided this template. This is intended to get your team conversing with each other, agree to certain questions, and to jumpstart the creation of your own Emergency Playbook. 
Remember, this is just a template; yours doesn’t have to adhere strictly to these sections nor be organized the way you see here. Feel free to adapt it (which is strongly encouraged!) to fit your needs._

_Remember: this can be changed as a team as many times as necessary!_


## Name your emergency procedure:
What is this emergency procedure called?

## Decision Trees
This section should determine whether or not to ignore your code review process. It answers the question **“What trigger conditions warrant an emergency scenario?”**. Feel free to add your own decision tree workflows here.




## Authorization Process
If you have confirmed a valid emergency, this next section details who is allowed to initiate an Emergency Playbook procedure and how to start one.


**Who is authorized to initiate an Emergency Playbook process?** (List out specific individuals.)







**How do you initiate an Emergency Playbook Process?** (Outline the exact steps to be used to invoke the emergency procedure. This definitely involves documentation, sometimes a series of approvals in tools, or a mix of both. )



## Bypassing Mechanism (and associated tasks)
Here, you should describe the actual bypassing mechanism – the temporary operations or access permitted because it is an emergency. In our case, we’re talking about bypassing the code review process you’ve established for your team.


**What’s our bypassing mechanism?** Some examples include:
- **Requiring a single approver**: More than one approval on a PR should be the standard. In the emergency scenario, a single approver can be used to expedite the review process. 
- **Requiring no approvers**: Not recommended; if choosing this as an option in your playbook, be sure to accompany it with lots of documentation and communication tasks.
- **Allowing a self-approval on own PR**: Justification steps should be put into place if choosing this option. For example, when a PR is detected to have been self-approved, an additional step should request the author to input a reason. Additionally, automated notifications should be reported to the team or tech lead/manager that a self-approval has occurred.
- **Allowing a manager or other stakeholder to approve a PR**: When there are no other choices, the pool of developers is small, or something really needs to get deployed, having a manager or other trusted stakeholder be an approver on a PR can be used as a bypassing mechanism as well. Justification steps should still be put into place, including the reason for requesting this particular approval.
- **Other**: If any of the above don’t work, describe YOUR team’s bypassing mechanism will be.

**What associated actions need to be taken?** (Outline exact steps. Consider: granting or temporary elevated permissions, creation of a temporary privileged account, or temporary reconfiguring or settings/tool configurations among other possibilities.) **Be sure to also list the range of time these actions are valid for and who is to perform these actions.**








## Next Steps
Once the bypassing mechanism (and its respective actions have been taken), describe what happens next. These includes three specific sections: Documentation, Communication, and Post-Incident Analysis:

### Documentation
While the person that initiates the emergency procedure can also carry it out, that’s not always what happens. What might be more likely is that a different person or group of people perform the actual bypassing mechanism (and its respective tasks/actions) than the one that initiates the emergency procedure. 

Some key items you seriously need to document:

- **Who** was involved?
- **Who** actually carried out the bypassing mechanism? 
- **What** was actually done? (Yes, the steps that should be done are the ones that need to be followed, but emergencies don’t always go according to plan! That’s why it’s important to log everything that happens, even deviations from the official actions. In the best case scenario, this log will look exactly like your bypassing mechanism steps. In the worst case, it will have a few more steps.)
- **What** temporary access/controls were granted?
- **Which** tools/accounts were affected?
- **When** (and if applicable, where) did this take place?
- **What** justified this emergency procedure? (This should be a link to the justification document we discussed earlier. Without this, your team should consider it a grave misuse of the emergency playbook)

Consider this the official **Emergency Procedure Execution Record** or EPER.

### Communication
Next,  communicate what actually happened. Depending on your organization, this can be a thorough and formal process or as simple as bringing it up at the next meeting. Be sure to check with your security and compliance teams to see if any formal report is needed from their end. This is where the Emergency Procedure Execution Record we discussed previously comes in real handy! The information captured there would be critical to have on any kind of report.

**Outline what those communication tasks are for your team here.**

Some examples include:

- Make Production Outage Record and Emergency Bypass Acknowledgement Record (if applicable) available in emergency channel/space.
- Send Incident Summary email to all affected teams.
- Send Resolution Summary email to affected customers.

### Post-incident Analysis
It’s important to do a post-incident analysis. From determining how well the emergency procedure worked to identifying improvement areas or needed changes, your team would benefit from holding this discussion shortly after an emergency playbook procedure is executed. 

**Outline when your team should do this and what questions you should try to answer when holding a post-incident analysis.**



