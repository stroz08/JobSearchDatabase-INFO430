# Job Search Database Build for INFO 430 Final Project

Tables (Create and populate):
- [x] UserType
- [x] Gender
- [x] MemebershipType
- [x] Membership
- [x] User

- [x] UserSeekingStatus
- [x] JobStatus
- [x] SeekingStatus
- [x] Status
- [x] UserJob

- [x] Role
- [x] Job
- [x] Employer
- [x] EmployerSize
- [x] Industry

- [x] Location
- [x] JobLocation
- [x] JobType
- [x] Level
- [x] Position



Business rules:
- [x] User cannot cancel and restart membership within 3 month period
- [x] Influencer can only apply to exec jobs
- [x] Age < 30 cannot apply to senior positions
- [x] Age <18 cannot apply to jobs
- [x] Age >24 cannot apply to internships
- [x] Any job higher than mid level cannot be part-time or intern or apprenticeship
- [x] One user cannot apply to same job twice
- [x] One user cannot be both recruiter and applicant for one job
- [x] One cannot apply to closed jobs
- [x] Exec position must have salary > 200k
- [x] All employers must have at least 1 US location
- [x] All US software engineer positions has salary > 80k


Computed columns:
- [X] Number of applicants for each job
- [X] Number of applicants for each company
- [X] Number of internship positions per company
- [x] Number of postings for each company
- [x] Number of postings for each job level
- [x] Total number of jobs with each job status
- [x] Number of members for each membership type
- [x] Number of female vs male applicant for a job
- [x] Number of female vs male applicant for an industry
