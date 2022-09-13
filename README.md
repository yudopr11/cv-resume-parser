# cv-resume-parser
Extract information from various resume or cv format into json format.

## Extracted Information
- filepath
- created
- face_photo
- phone_number
- email
- estimated_working_year_experience
- working_experience
- website
- skills
- education

## Output Example
```python
{
  "filepath": "/content/drive/MyDrive/Project/!Playground/CV/Yudho Prakoso-resume.pdf",
  "created": "2022-09-13 22:00:35.039562+07:00",
  "photo": "/content/drive/MyDrive/Project/!Playground/Face/Yudho Prakoso-resume.pdf.jpg",
  "phone_number": "82214886517",
  "email": "yudopr10@gmail.com",
  "estimated_working_year_experience": "4",
  "working_experience": [
    "lead",
    "tutor"
  ],
  "website": [
    "https://www.linkedin.com/in/yudho-prakoso-a057a323b/",
    "https://freecodecamp.org/certification/",
    "https://doi.org/10.1145/3239283.3239297"
  ],
  "skills": [
    "data science",
    "excel",
    "sql server",
    "ui",
    "analysis",
    "pentaho",
    "python",
    "teaching",
    "c",
    "information technology",
    "postgresql",
    "project management",
    "sql",
    "mysql",
    "mathematics",
    "etl",
    "plan",
    "tableau",
    "google sheets",
    "bigquery"
  ],
  "education": [
    {
      "college": "universitas indonesia",
      "major": "mathematics",
      "degree": "bachelor"
    }
  ]
}
```

## Notes
To detect colleges, majors, skills, and work experience based on reference files. If it is not detected, it can be added to the reference files.
