# Recruitment Agency Management Software

Recruit Pro is a recruitment platform for staffing agencies and placement consultancies. It's built with Laravel 12, Livewire 3 and Tailwind CSS, runs in the browser and installs as an app (PWA). It combines a public job board, an applicant tracking system (ATS) with a kanban pipeline, a client (employer) portal, a jobseeker portal and a complete agency back office. It covers job posting and moderation, interviews, a talent pool with Boolean search, offer letters, joining documents, placements with replacement guarantees, client contracts, GST invoices with TDS and payments, recruiter targets and commission, campus drives, chat and notifications. It fully supports Indian GST, including CGST, SGST and IGST, with invoices numbered per financial year. There are reports with CSV export, an audit trail of every change, and five user roles with an editable permission matrix. It is a good fit for recruitment agencies, staffing firms, manpower consultancies and HR outsourcing companies. Buyers get the complete source code for a one-time payment, with one year of free updates and email support.

<img src="https://www.coderobotics.com/product/recruitment-agency-software">

Most job portal scripts stop at "post a job, receive applications". A real recruitment agency needs much more: clients to manage, candidates to move through interviews, offer letters to send, joining documents to check, placement fees to invoice with GST, and recruiter commission to pay. Usually that means a job board, a spreadsheet, an accounting tool and a lot of email. Recruit Pro was built for that. Agency staff, client companies and candidates each get their own workspace, and the agency sees the whole process, from application to joining to payment, in one place. Every page works on phones.

What You Get
 
Agency website: a one-page website with Home, About, Services, Jobs, How it Works, Testimonials, FAQ and Contact sections. Contact form messages are saved and every admin is notified.
Public job board: jobs, companies, categories, cities and blog pages, built for search engines, with a sitemap.
Flexible sign-in: email and password, a 6-digit email one-time code, and Google / LinkedIn sign-in. Sign-in attempts are rate-limited.
Client management: client companies with KYC (GSTIN / PAN), account managers, and invitations for client users to the portal.
Job posting and moderation: approve or reject with a reason, feature, hold or close jobs. The job form scores SEO and quality live as you type.
Kanban hiring pipeline: Applied, Under Review, Shortlisted, Interview, Offered, Hired and Rejected. Drag and drop on desktop, or a stage menu on phones. Ratings, reject reasons, and adding candidates from the talent pool.
Interviews: schedule, reschedule, cancel and record outcomes, with agenda tabs for today, upcoming, needs outcome and past.
Talent pool: Boolean search (PHP AND Laravel, React NOT Angular, "phrase" OR term), segments, filters and CSV export.
Client (employer) portal: post jobs (always reviewed before publishing), review shortlisted candidates, request an interview or offer, decline with feedback, and download invoices. Candidate contact details stay hidden unless the candidate opts in.
Jobseeker portal: a section-by-section profile builder with a live completion checklist, up to 5 resumes with one-tap apply, applications, saved jobs, profile views and analytics.
Job alerts: up to 10 alerts per jobseeker with live match counts, emailed daily or weekly.
Points, badges and referrals: 5 levels, 10 badges, a points history, and a refer-and-earn code that rewards both friends.
Offer letters: draft, preview and send offer letters as PDFs. Candidates accept or decline online, and unanswered offers expire automatically.
Joining documents: candidates upload documents, recruiters verify or reject them, and confirming the joining creates the placement, fee and commission.
Placements and guarantees: replacement guarantee tracking, invoice status, and marking a candidate as left during the guarantee.
Client contracts: % of CTC or fixed fee, replacement guarantee period, payment terms and a signed copy.
GST invoices: CGST + SGST within your state or IGST for other states, chosen automatically from the client's GSTIN or state. Invoices are numbered per financial year (e.g. RP/26-27/0001), with payments, TDS and overdue tracking.
Targets and commission: monthly placement and revenue targets per recruiter, achievement tracking, and commission that is approved when the guarantee ends and reversed if the candidate leaves.
Reports with CSV export: placements per month, invoiced vs collected, hiring funnel, time to hire, sources, receivables ageing and top clients.
QR verification: offer letters and invoices carry a QR code. Scanning it shows a few masked facts proving the document is genuine.
Passes and check-in: interview and campus passes with QR code and barcode, scanned at the desk with a USB scanner, a typed code or a phone camera.
Campus drives: campus recruitment drives with a public registration page, bulk status updates, CSV export, and adding students straight into a job pipeline.
Content and SEO: blog with a rich-text editor and scheduled publishing, CMS pages and footer links, SEO landing pages built from job filters, a keyword tracker, and city SEO settings.
Chat: a Messages page for every role, with PDF, Word and image sharing. Clients and candidates only talk to agency staff, never to each other, and people who are away get an email.
Notifications: a live notification bell, unread message counter, toasts, desktop alerts and email alerts.
Installable app with offline mode: install the site as an app. Jobseekers, recruiters and clients can read their saved pages without internet, and saved pages are cleared on sign-out.
Users and audit trail: invite staff, change roles, suspend or activate users, a permission matrix for admins and recruiters, and a record of who changed what and when, with before and after values.
Settings: contact details, social links, legal, GST and bank details for invoices, all website text, and system health.
Full demo data: 10 clients, 36 jobs, 32 candidates, about 100 applications, 24 placements, 21 GST invoices, campus drives, blog posts and chat conversations, ready to explore.

Why Recruit Pro?
 
Recruitment agencies often run on a job board, a spreadsheet of candidates, an accounting tool for invoices and email for everything else. Recruit Pro puts all of that in one place:

Built for agencies, with separate workspaces for agency staff, client companies and candidates.
The full hiring process, from job posting to joining, placement, invoice and payment.
Indian GST built in, including IGST for other states and financial-year invoice numbering.
Strict privacy: clients only see shortlisted candidates, and contact details stay hidden unless the candidate opts in.
Audit trail for every change, so there are no unexplained edits.
Tested: 137 automated PHPUnit tests, an access check of every page for every role, and browser end-to-end tests of the full hiring journey on desktop and phone widths.
Installs like an app on desktops, tablets and phones.

Perfect For
 
Recruitment agencies and staffing firms
Placement consultancies and manpower agencies
HR outsourcing and executive search firms
Campus recruitment and training-and-placement teams
Businesses in India that need GST invoices for placement fees
Developers and agencies building recruitment or job portal solutions for clients
Students and learners studying Laravel, Livewire and PWA architecture

Tech Stack
 
Laravel 12 (PHP 8.2+)
Livewire 3
Alpine.js
Tailwind CSS v4
MySQL / MariaDB
spatie/laravel-permission (roles and permissions)
owen-it/laravel-auditing (audit trail)
barryvdh/laravel-dompdf (offer letters, invoices and passes as PDF)
picqer/php-barcode-generator (barcodes)
chillerlan/php-qrcode (QR codes)
Service Worker + Web App Manifest (PWA and offline mode)
PHPUnit and Puppeteer (automated testing)

Prerequisites
 
PHP 8.2 or higher with pdo_mysql, intl, gd, mbstring, fileinfo and zip
Composer 2
Node.js 20+ and npm
MySQL 8 or MariaDB 10.4+ (XAMPP works)
HTTPS in production, for app install, offline mode and camera scanning
A cron entry for the Laravel scheduler (job alerts and daily offer and guarantee checks)

More details and download link:
https://www.coderobotics.com/product/recruitment-agency-software
