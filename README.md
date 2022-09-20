# cv-resume-parser
Extract information from various resume or cv format into json format.

## Extracted Information
- filepath
- created
- face_photo
- phone_number
- email
- estimated_working_year_experience
- work_experience
- website
- skills
- education

## Output Example
```python
{
  "filepath": "/content/drive/MyDrive/Project/!Playground/CV/Yudho Prakoso-resume.pdf",
  "created": "2022-09-20 17:01:11.625169+07:00",
  "face_photo": "/content/drive/MyDrive/Project/!Playground/Face/Yudho Prakoso-resume.pdf.jpg",
  "phone_number": "82214886517",
  "email": "yudopr10@gmail.com",
  "estimated_working_year_experience": "7",
  "work_experience": [
    "content ops lead",
    "mathematics teacher",
    "mathematics tutor"
  ],
  "website": [
    "https://www.linkedin.com/in/yudho-prakoso-a057a323b/",
    "https://freecodecamp.org/certification/",
    "https://doi.org/10.1145/3239283.3239297"
  ],
  "skills": [
    "mysql",
    "bigquery",
    "information technology",
    "data science",
    "ui",
    "c",
    "project management",
    "google sheets",
    "analysis",
    "python",
    "excel",
    "plan",
    "mathematics",
    "sql server",
    "etl",
    "tableau",
    "sql",
    "pentaho",
    "postgresql",
    "teaching"
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
To detect colleges, majors, skills, and working experience based on reference files. If it is not detected, it can be added to the reference files.
