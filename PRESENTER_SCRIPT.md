# Scope’s first day — 10-minute presenter script

This is a scripted simulation. Pacing includes audience pauses and clicks.

## 0:00-1:00 | 1. Intro | Scope’s first day

**SAY**

Meet Scope, our orange cat and today's AI assistant. It's Scope's first day on the identity desk, and the first job sounds easy: Alex Morgan is moving from Sales to Engineering. Update Alex's department. Scope knows exactly what we want. But knowing the task and being allowed to do it are two different things. Today we're using a scripted simulation inspired by Okta Managed MCP Server. No tenant connection is needed. We'll try the same profile change with two ready-made connections: read-only and edit access. Same person. Same request. Before we click, what do you think will happen? Can Scope complete the job through both connections? In the next few minutes, we'll review the requests, compare the outcomes and check Alex's sample profile. Let's give Scope the first task.

**DO**

Keep the Intro screen visible. At the end, pause for the audience to predict the outcome. Click Next: Read-only.

## 1:00-3:00 | 2. Read-only | Scope meets the boundary

**SAY**

Here is Scope's first connection. It is already set up for this demo. The operator is Sam, our demo administrator, and the connection can view profiles. Alex's current department is Sales. The request is to change it to Engineering. Everything about the task is clear. Take a quick look at the request before we run it.

**CLICK**

Try the request. In the review window, point to Alex, the department change and Read-only connection.

**SAY**

This review is part of our demonstration interface. It helps us check the request, but it does not grant any extra permission. We are still using the read-only connection. What do you expect Scope to do now?

**PAUSE**

Give the audience 10 seconds to answer. Then click Run simulated request.

**SAY**

Change blocked. Scope understood the task, but the connection could not edit the profile. Alex's sample department was left unchanged. Scope's reaction is simple: I can look, but I can't change it. That is the first lesson. A clear instruction does not expand the access available to the assistant. We don't need a more persuasive prompt. We need to use an appropriately configured connection for the task.

**DO**

Leave the blocked result visible for 10 seconds. Click Next: Edit access.

## 3:00-6:00 | 3. Edit access | Scope gets the right connection

**SAY**

Now I, as the presenter, select the second preconfigured connection. This one can edit profiles in the simulation. The operator stays the same. Alex stays the same. The requested department change stays the same. We are not rewriting the task or changing the target. We are changing the connection used to carry it out.

**CLICK**

Try the request. Show Editor connection in the review window. Read the same department change, then click Run simulated request.

**SAY**

Change allowed. Scope can now carry out the sample update. That is a useful result, but let's finish the job properly. A success message tells us that the simulated request completed. We should also look at the sample profile and see what is there now. Scope has one more step before celebrating.

**CLICK**

Check profile. Point to Before: Sales and After: Engineering.

**SAY**

Here is the before-and-after view. Alex was in Sales. Alex is now in Engineering. The sample profile has been checked. That makes the story easy to follow: an explicit task, an access decision and a check of the affected data. Scope did not grant itself new access. We used a different connection that was prepared for this task. In a real Managed MCP setup, the actual decision also depends on the operator's permissions and the state of the resource. The simulated connections here make the main idea easy to see.

**ASK**

Which step mattered most to you: reviewing the request, checking access, or verifying the profile? Allow 20-30 seconds for answers.

**DO**

Summarize one response. Click Next: Results by 6:00.

## 6:00-8:00 | 4. Results | One task, two outcomes

**SAY**

Let's put both outcomes beside each other. On the left, the read-only connection blocked the change. On the right, the editor connection allowed it, and the sample profile was checked. Scope had the same intention in both cases. The request and demo operator stayed the same. The access available through the connection changed.

**DO**

Point to Change blocked, then Change allowed. Keep the comparison screen visible.

**SAY**

This is the permission story we want people to remember. Assistants need a useful way to reach identity operations, and the connection needs access suitable for the action. Okta Managed MCP Server provides a standard connection to Okta tools. In a live deployment, the authenticated context and input checks matter. Here, we have made that idea visible with a scripted simulation. These cards are simulated outcomes, not live Okta evidence or audit records.

**ASK**

What task in your environment would you want an assistant to help with, while keeping clear limits on its access? Allow about 30 seconds.

**SAY**

That is the conversation this demo is designed to start. A familiar task is easier to discuss when everyone can see the access boundary. Scope makes it memorable; the two outcomes make the point.

**DO**

Click Next: Close by 8:00.

## 8:00-10:00 | 5. Close | The lesson Scope takes home

**SAY**

Scope's first day is complete. One colleague changed teams. One assistant understood the request. The read-only connection blocked the update. The editor connection allowed it, and we checked the sample profile. The lesson is simple: give AI a useful task and keep access in control. Scope can be enthusiastic, helpful and a little mischievous. The connection still needs the right authority for the job.

**PAUSE**

Pause for five seconds. Let the closing line remain visible.

**SAY**

We used a simulation today so that any presenter can show this story without tenant setup or a connection problem interrupting the flow. A live customer evaluation should validate the real connection, the actual scopes and operator permissions, and the returned results for the intended use case. This simulator is a reusable way to introduce that discussion. And Scope has already asked for the next task: access to the snack cupboard. We will review that request separately.

**ASK**

Take one question. If none comes, ask: Which identity task would you start with? Use the remaining time for the answer.

**CLOSE**

Thank you. Happy to explore how this would map to your own environment.

**AFTER THE DEMO**

Click Restart demo when you are ready for the next rehearsal. This resets the sample profile and both outcomes.