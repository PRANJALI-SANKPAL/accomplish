# Prompt 05 — LOG APPLICATION

```text
TASK: Produce a CSV row for career-job-os/08-trackers/applications.csv

Columns:
date,company,role_title,job_id,url,tier,fit_score,resume_version,referral_status,channel,status,next_action_date,notes

Fill from user inputs. status default=APPLIED.
referral_status one of: NONE, ASKED, REFERRED, DECLINED
channel: PORTAL|LINKEDIN|NAUKRI|INSTAHYRE|WELLFOUND|EMAIL|OTHER

Also produce referrals.csv row if ask was sent.
```
