# Week 7｜Slack / Jira 更新信息句型模板

> 适用场景：Daily update、故障排查同步、跨团队对齐、handoff 交接。

## 1) Slack - Status Update（日常进度）
- Quick update: I finished **[task]**, and I’m now working on **[next task]**.
- I’m currently on track for today’s goal: **[goal]**.
- I’ve completed **[A/B]**; next I’ll focus on **[C]**.
- ETA for this item is **[time/date]**.

## 2) Slack - Blocker / Risk（阻塞与风险）
- I’m currently blocked by **[issue]**.
- The main risk right now is **[risk]**, which may impact **[scope/timeline]**.
- I’ve reproduced the issue in **[env]** and I’m checking **[logs/configs/metrics]**.
- If needed, I may need support from **[@team/person]** on **[dependency]**.

## 3) Slack - Follow-up（追更与下一步）
- I’ll share another update in **[30 mins / 1 hour]**.
- I’ll follow up once I confirm the root cause.
- I’ll post the fix plan and rollback plan before execution.
- I’ll keep everyone posted if scope or ETA changes.

## 4) Jira Comment - Progress（Jira 进度评论）
- **Progress:** Completed **[x]**, currently working on **[y]**.
- **What changed:** Updated **[component/config/PR]**.
- **Validation:** Tested in **[env]**, result is **[pass/fail + detail]**.
- **Next step:** **[next action]**, ETA **[time/date]**.

## 5) Jira Comment - Bug / Incident（缺陷与事故）
- **Issue summary:** Observed **[symptom]** in **[service/env]**.
- **Impact:** Affects **[users/services]**; severity **[S1/S2/S3]**.
- **Investigation:** Checked **[logs/trace/metrics]**; current hypothesis is **[hypothesis]**.
- **Mitigation:** Applied **[temporary action]** to reduce impact.
- **Next update:** by **[time/date]**.

## 6) Jira Comment - Handoff（交接信息）
- **Current status:** **[done/in progress/blocked]**.
- **Context:** Please continue from **[branch/PR/ticket]**.
- **Open items:** **[todo1, todo2]**.
- **Notes:** Watch out for **[risk/dependency]**.

## 7) 高频可替换短语（句型拼装）
- I confirmed that ...
- It looks like ...
- The issue seems to be related to ...
- I’ve narrowed it down to ...
- As a workaround, we can ...
- I’ll prioritize this and update again by ...
