&#x20;Day 1 - 2 Oct 2026



&#x20;What I did

\- Created an AWS account through the new sign-up, using my Google login

\- Confirmed I'm on the Free plan with $100 in credits

\- Added MFA to the account

\- Tried to create an IAM admin user, but it had no console password

\- Diagnosed WSL: Ubuntu is installed, but it times out on start

\- Set up Git Bash and created the repo `gloria-cloud-engineering-90`

\- Added the 5 folders and a README, then pushed to GitHub

\- Wrote my first learning-log entry



&#x20;What I learnt

\- AWS now has a newer sign-up where a Google login is the identity and a "project" holds the account. It's different from the classic root user + IAM user setup

\- The Free plan can't bill me, but the account closes after 6 months or when the credits run out

\- Git doesn't track empty folders, so I need `.gitkeep` files

\- Only the `.pub` SSH key is ever shared. The private key stays on my laptop

\- Don't run `wsl --unregister`, because it deletes everything inside Ubuntu



&#x20;What confused me

\- Why the IAM user had no password option

\- The WSL error `HCS\_E\_CONNECTION\_TIMEOUT` and the failed update (exit code 1603)

\- How the MFA I added relates to the new project-based sign-in



&#x20;What I need to revisit

\- Fix WSL after a proper restart (`wsl --update`)

\- Check Google 2-Step Verification on the account I used for AWS

\- Look at Manage projects and the billing controls

\- Decide whether to delete the unused `gloria-admin` IAM user



&#x20;What I'm doing tomorrow

\- Day 2: IAM, EC2, S3, and CloudWatch

