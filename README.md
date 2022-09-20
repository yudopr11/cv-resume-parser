# cv-resume-parser
Extract information from various resume or cv format into json format.

## Extracted Information
- filepath
- created
- face_photo
- phone_number
- email
- website
- estimated_working_year_experience
- work_experience
- education
- skills

## Output Example
```python
{
  "filepath": "/content/drive/MyDrive/Project/!Playground/CV/Yudho Prakoso-resume.pdf",
  "created": "2022-09-20 19:44:02.890281+07:00",
  "face_photo": "/content/drive/MyDrive/Project/!Playground/Face/Yudho Prakoso-resume.pdf.jpg",
  "phone_number": "82214886517",
  "email": "yudopr10@gmail.com",
  "website": [
    "https://www.linkedin.com/in/yudho-prakoso-a057a323b/",
    "https://freecodecamp.org/certification/",
    "https://doi.org/10.1145/3239283.3239297"
  ],
  "estimated_working_year_experience": "7",
  "work_experience": [
    "mathematics tutor",
    "content ops lead",
    "mathematics teacher"
  ],
  "education": [
    {
      "college": "universitas indonesia",
      "major": "mathematics",
      "degree": "bachelor"
    }
  ],
  "skills": [
    "analysis",
    "bigquery",
    "c",
    "data science",
    "etl",
    "excel",
    "google sheets",
    "information technology",
    "mathematics",
    "mysql",
    "pentaho",
    "plan",
    "postgresql",
    "project management",
    "python",
    "sql",
    "sql server",
    "tableau",
    "teaching",
    "ui"
  ]
}
```

## Notes
To detect colleges, majors, skills, and working experience based on reference files. If it is not detected, it can be added to the reference files.
