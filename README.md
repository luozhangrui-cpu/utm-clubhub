# UTM ClubHub

UTM ClubHub is a website for managing club and society activities at UTM Kuala Lumpur. Students, club committees, advisors and HEP can handle every step of an activity in one place, from joining a club to receiving merit points and an e-certificate.

This is the project repository of Group D, SCSE2243 Application Development Project I, Section 16, Semester I 2026/2027.

## Team

| Member | Subsystem | Branch |
| --- | --- | --- |
| LIU XINGYU | User and Membership Management | `feature/user-membership` |
| LIU ZHUOHAN | Club Management | `feature/club-management` |
| LUO ZHANGRUI | Event Management | `feature/event-management` |
| LIU LIKAI | Attendance and Merit | `feature/attendance-merit` |
| YU HANG | Analytics and Reporting | `feature/analytics-reporting` |

## Module index

Quick links to the frontend script of each module.

| Module | Frontend Script |
| --- | --- |
| Authentication and Authorisation | [Authentication.jsx](frontend/src/modules/user-membership/Authentication.jsx) |
| Profile Management | [Profile.jsx](frontend/src/modules/user-membership/Profile.jsx) |
| Membership Management | [Membership.jsx](frontend/src/modules/user-membership/Membership.jsx) |
| Club Directory and Profile | [ClubDirectory.jsx](frontend/src/modules/club-management/ClubDirectory.jsx) |
| Committee Management | [Committee.jsx](frontend/src/modules/club-management/Committee.jsx) |
| Announcement and Notification | [Announcement.jsx](frontend/src/modules/club-management/Announcement.jsx) |
| Event Proposal and Approval | [EventProposal.jsx](frontend/src/modules/event-management/EventProposal.jsx) |
| Event Publishing and Registration | [EventRegistration.jsx](frontend/src/modules/event-management/EventRegistration.jsx) |
| Event Calendar | [EventCalendar.jsx](frontend/src/modules/event-management/EventCalendar.jsx) |
| QR Attendance | [QrAttendance.jsx](frontend/src/modules/attendance-merit/QrAttendance.jsx) |
| Merit Point Tracking | [MeritPoints.jsx](frontend/src/modules/attendance-merit/MeritPoints.jsx) |
| e-Certificate Generation | [ECertificate.jsx](frontend/src/modules/attendance-merit/ECertificate.jsx) |
| Club Activity Dashboard | [ClubDashboard.jsx](frontend/src/modules/analytics-reporting/ClubDashboard.jsx) |
| Participation Analytics | [ParticipationAnalytics.jsx](frontend/src/modules/analytics-reporting/ParticipationAnalytics.jsx) |
| Report Generation and Export | [ReportExport.jsx](frontend/src/modules/analytics-reporting/ReportExport.jsx) |

## Technology

React with Vite and Tailwind CSS for the front end, Node.js with Express for the back end, and MySQL for the database.

## How we work

Each member works on their own branch and does not push directly to `main`. When a module is ready, the member opens a pull request, another member reviews it, and then it is merged into `main`.

Commit messages follow the format `type: short description`, for example `feat: add event registration form` or `fix: show error for empty username`. Common types are `feat`, `fix`, `update`, `refactor`, `docs` and `test`.
