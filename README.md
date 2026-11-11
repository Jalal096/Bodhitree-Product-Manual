# BodhiTree Product Manual & Instructor Guide

Welcome to the **BodhiTree Instructor Guide and Product Manual**. BodhiTree is an interactive e-learning platform developed at IIT Bombay for online learning, with interactive videos and in-video quizzes, programming labs, and learning activities. BodhiTree helps students move beyond watching content to actively practising, experimenting, and applying what they learn. This manual provides instructors, teachers, and teaching assistants (TAs) with a complete walkthrough of course setup, learning content management, lab exercises, and student evaluation.

> [!NOTE]
> This manual covers the core teaching tools on BodhiTree:
>
> * **Course Setup & Management** (creating courses, managing settings, publish controls)
> * **Multimedia Book (MMB)** (chapters, sections, documents, videos, URLs, and in-book quizzes)
> * **Multimedia Quiz Editor** (creating question modules and questions directly via the web UI)
> * **In-Video Quizzes** (timeline markers, video checkpoints, and inline editing)
> * **Labs Management** (creating labs, bulk show/hide actions)
> * **Programming Activities** (problem setup, template code, visible and hidden test cases, autograding)
> * **Lab Quizzes** (timed lab assignments created via the web UI or `.odt` templates)
> * **Submissions & Grading** (lab overview submissions, programming code viewer and test runs, quiz submissions, and Force Run re-evaluation)
> * **People & Enrollment** (single student enrollment, searching existing users, STA/JTA roles, and bulk CSV upload)
> * **Course Settings & Protection** (general course details, forum moderation, and disabling file downloads)
> * **Interactions** (discussion forums and class announcements)
> * **Performance & Grades** (gradebook table and CSV export)
> * **Recycle Bin** (restoring deleted lab activities)

---

## Table of Contents

* [Section 1: Getting Started &amp; Signing In](#section-1-getting-started--signing-in)
  * [1.1 Accessing the BodhiTree Portal](#11-accessing-the-bodhitree-portal)
  * [1.2 Signing In with Your Instructor Account](#12-signing-in-with-your-instructor-account)
* [Section 2: Course Dashboard &amp; Course Management](#section-2-course-dashboard--course-management)
  * [2.1 The My Courses Dashboard](#21-the-my-courses-dashboard)
  * [2.2 Creating a New Course Offering](#22-creating-a-new-course-offering)
  * [2.3 Course Card Options (Three-Dot Menu)](#23-course-card-options-three-dot-menu)
* [Section 3: Course Navigation Overview](#section-3-course-navigation-overview)
  * [3.1 The Course Sidebar Navigation](#31-the-course-sidebar-navigation)
  * [3.2 Organization of Menu Items](#32-organization-of-menu-items)
* [Section 4: The Multimedia Book (MMB): Chapters &amp; Sections](#section-4-the-multimedia-book-mmb-chapters--sections)
  * [4.1 Book Organization &amp; Structure](#41-book-organization--structure)
  * [4.2 Creating a New Chapter](#42-creating-a-new-chapter)
  * [4.3 Managing Chapters &amp; Adding Sections](#43-managing-chapters--adding-sections)
* [Section 5: Adding Learning Materials (Sections, In-Book Quizzes, Documents, Videos &amp; URLs)](#section-5-adding-learning-materials-sections-in-book-quizzes-documents-videos--urls)
  * [5.1 The Add Content Menu](#51-the-add-content-menu)
  * [5.2 Adding a Section](#52-adding-a-section)
  * [5.3 Adding an In-Book Quiz](#53-adding-an-in-book-quiz)
  * [5.4 Adding a Document (File Attachments)](#54-adding-a-document-file-attachments)
  * [5.5 Adding a Video Lecture](#55-adding-a-video-lecture)
  * [5.6 Adding External Web URLs](#56-adding-external-web-urls)
* [Section 6: The Multimedia Quiz Editor: Generating Quizzes via UI](#section-6-the-multimedia-quiz-editor-generating-quizzes-via-ui)
  * [6.1 Purpose of the Quiz Editor](#61-purpose-of-the-quiz-editor)
  * [6.2 Organizing Questions with Modules](#62-organizing-questions-with-modules)
  * [6.3 Adding and Configuring Questions](#63-adding-and-configuring-questions)
  * [6.4 Understanding Hints, Answer Descriptions, and Error Descriptions](#64-understanding-hints-answer-descriptions-and-error-descriptions)
* [Section 7: In-Video Quizzes &amp; Timeline Markers](#section-7-in-video-quizzes--timeline-markers)
  * [7.1 Purpose of In-Video Quizzes](#71-purpose-of-in-video-quizzes)
  * [7.2 The Video Player Workspace](#72-the-video-player-workspace)
  * [7.3 Section Markers vs. Quiz Markers](#73-section-markers-vs-quiz-markers)
  * [7.4 Adding, Editing, and Deleting Markers (CRUD Operations)](#74-adding-editing-and-deleting-markers-crud-operations)
* [Section 8: Labs Management &amp; Bulk Actions](#section-8-labs-management--bulk-actions)
  * [8.1 The Labs Dashboard](#81-the-labs-dashboard)
  * [8.2 Creating a New Lab](#82-creating-a-new-lab)
  * [8.3 Bulk Show &amp; Hide Operations](#83-bulk-show--hide-operations)
  * [8.4 Inside a Lab: Activities, Editing, and Actions](#84-inside-a-lab-activities-editing-and-actions)
* [Section 9: Programming Activities &amp; Autograding](#section-9-programming-activities--autograding)
  * [9.1 What is a Programming Activity?](#91-what-is-a-programming-activity)
  * [9.2 Problem Statements, Template Code, and Instructor Solutions](#92-problem-statements-template-code-and-instructor-solutions)
  * [9.3 Configuring Test Cases: Visible vs. Hidden](#93-configuring-test-cases-visible-vs-hidden)
  * [9.4 Setting Resource Limits](#94-setting-resource-limits)
* [Section 10: Lab Quizzes: Creation &amp; Authoring](#section-10-lab-quizzes-creation--authoring)
  * [10.1 Important Difference: In-Book Quiz vs. Lab Quiz](#101-important-difference-in-book-quiz-vs-lab-quiz)
  * [10.2 Creating a Lab Quiz Activity](#102-creating-a-lab-quiz-activity)
  * [10.3 Authoring Questions via Web UI Quiz Editor](#103-authoring-questions-via-web-ui-quiz-editor)
* [Section 11: Submissions Management &amp; Student Evaluation](#section-11-submissions-management--student-evaluation)
  * [11.1 Overall Lab Submissions &amp; Exporting Reports](#111-overall-lab-submissions--exporting-reports)
  * [11.2 Programming Submissions &amp; Subjective Grading](#112-programming-submissions--subjective-grading)
  * [11.3 Lab Quiz Submissions &amp; Individual Grading](#113-lab-quiz-submissions--individual-grading)
* [Section 12: People &amp; Student Enrollment](#section-12-people--student-enrollment)
  * [12.1 The People Dashboard](#121-the-people-dashboard)
  * [12.2 Single User Enrollment (New User &amp; Existing User Search)](#122-single-user-enrollment-new-user--existing-user-search)
  * [12.3 Bulk CSV Student Upload](#123-bulk-csv-student-upload)
  * [12.4 Course Roles: Students, TAs (STA / JTA), and Instructors](#124-course-roles-students-tas-sta--jta-and-instructors)
* [Section 13: Course Settings &amp; Content Protection](#section-13-course-settings--content-protection)
  * [13.1 General Course Settings](#131-general-course-settings)
  * [13.2 Multimedia Book Settings](#132-multimedia-book-settings)
  * [13.3 Discussion Forum Settings](#133-discussion-forum-settings)
  * [13.4 Content Protection](#134-content-protection)
* [Section 14: Interactions: Discussion Forums &amp; Announcements](#section-14-interactions-discussion-forums--announcements)
  * [14.1 Class Discussion Forum](#141-class-discussion-forum)
  * [14.2 Course Announcements](#142-course-announcements)
* [Section 15: Performance Tracking &amp; Gradebook](#section-15-performance-tracking--gradebook)
  * [15.1 Grades Dashboard](#151-grades-dashboard)
  * [15.2 Exporting Grades to CSV](#152-exporting-grades-to-csv)
* [Section 16: Recycle Bin &amp; Common Troubleshooting](#section-16-recycle-bin--common-troubleshooting)
  * [16.1 Restoring Deleted Items from Recycle Bin](#161-restoring-deleted-items-from-recycle-bin)
  * [16.2 Common Issues &amp; Quick Solutions](#162-common-issues--quick-solutions)

---

## Section 1: Getting Started & Signing In

BodhiTree is an interactive e-learning platform developed at IIT Bombay. It allows teachers to build structured course textbooks, conduct coding labs with instant automated evaluation, share videos with in-video checkpoints, and review student grades in one place.

### 1.1 Accessing the BodhiTree Portal

To access BodhiTree, open your web browser (Google Chrome or Mozilla Firefox work best) and type the web address given by your institution (for example, `https://tiger.bodhi-tree.in`).

![Figure 1: BodhiTree Landing Page](screenshots/fig_1_landing_page.png)
*Figure 1: BodhiTree Landing Page with Login button.*

As shown in **Figure 1**, the landing page displays general platform information. In the top-right corner of the navigation bar, you will find the **Login** button.

---

### 1.2 Signing In with Your Instructor Account

1. Click the **Login** button on the top-right navigation bar (**Figure 1**).
2. The sign-in dialog opens in the center of your screen, as shown in **Figure 2**.
3. In the **Email** field, enter your registered email address (e.g. `abc@example.com`).
4. In the **Password** field, enter your password.
5. Click the blue **Sign In** button.

![Figure 2: Sign In Dialog](screenshots/fig_2_login_modal.png)
*Figure 2: BodhiTree Sign In Dialog for entering email and password.*

> [!TIP]
> BodhiTree automatically keeps your login session active in your browser. You do not need to sign in repeatedly when opening different courses or chapters. If you stay away for several days, your session will automatically time out for security, and you can simply log in again.

---

## Section 2: Course Dashboard & Course Management

After logging in, BodhiTree takes you to the **My Courses** dashboard. This is your home screen where every course you teach or manage is listed.

![Figure 3: My Courses Dashboard](screenshots/fig_3_my_courses_dashboard.png)
*Figure 3: My Courses Dashboard showing course cards, search bar, and Add Course button.*

---

### 2.1 The My Courses Dashboard

As shown in **Figure 3**, the dashboard has three main areas:

* **Course Cards:** Every course is shown as a card displaying the Course Code, Course Title, and Institution name. If the course is not published yet, you will see a green **Publish** button to make it visible in the Explore catalog. Once published, the card displays a green published badge.
* **Search Courses Input:** Located at the top-left, this search bar lets you find any course instantly by typing its code (like `CS101`) or title keyword.
* **+ Add Course Button:** Located at the top-right, this blue button opens the course creation form.

---

### 2.2 Creating a New Course Offering

To create a new course:

1. Click the **+ Add Course** button on the dashboard (**Figure 3**).
2. The **Add Course** popup dialog appears on your screen, as shown in **Figure 4**.

![Figure 4: Add Course Modal](screenshots/fig_4_add_course_modal.png)
*Figure 4: Add Course Dialog with Course Image, Course Code, and Enrollment Type.*

3. Fill in the fields:
   * **Course Image:** Drag and drop or browse an image file (such as `.png`, `.jpg`, or `.webp`). This image acts as the poster on the course card shown on your dashboard and the course catalog.
   * **Course Code:** Enter a unique identifier up to 8 characters for your course (e.g., `CS101`, `EE204`, or `MAIN101`).
   * **Course Name:** Enter the full course title (e.g., `Computer Programming Fundamentals`).
   * **Institute & Department:** Select your institution and academic department from the dropdown menus.
   * **Enrollment Type:** Choose between:
     * **Open Course:** Any student registered on the portal can click and join the course directly.
     * **Moderated Course:** Students can request to join, but an instructor or TA must review and approve their request before they get access.
   * **Course Content:** Select **Create on own** to start with a blank course, or choose **Import using File** or **Import using URL** to bring in an existing course archive.
   * **Discussion Forum Settings:** Select whether email notifications are sent to everyone for every discussion post, and whether to show the identity of anonymous posts to the instructor.
4. Click the blue **Add Courses** button inside the modal to save.
5. Your new course card will appear on the dashboard right away.

> [!IMPORTANT]
> Course codes must be unique in your institution. If another course is already using that exact code, the system will show an error asking you to choose a different course code.

---

### 2.3 Course Card Options (Three-Dot Menu)

On every course card (shown in **Figure 3**), there is a three-dot menu button (`⋮`) in the top-left corner. Clicking it reveals two actions:

1. **Download Course:** Creates and downloads an archive file containing the course structure and materials.
2. **Delete Course:** Permanently deletes the course and all its student records from the database.

> [!NOTE]
> There is **no Edit Course option** inside the three-dot menu on the course card. If you want to change the course name, description, or enrollment mode, open the course and go to **Course Settings** (described in [Section 13.1](#131-general-course-settings)).

---

## Section 3: Course Navigation Overview

Click on any course card from your dashboard to enter that course workspace. The left sidebar gives you quick access to all parts of the course.

![Figure 5: Course Sidebar Navigation](screenshots/fig_5_course_navigation.png)
*Figure 5: Course Workspace Sidebar showing navigation sections.*

---

### 3.1 The Course Sidebar Navigation

As shown in **Figure 5**, the sidebar organizes your course into distinct functional areas.

### 3.2 Organization of Menu Items

| Section                     | Menu Option                    | What It Is Used For                                                                                                                                                                |
| :-------------------------- | :----------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Course Content**    | **Multimedia Book**      | The digital textbook view. Contains chapters, sections, lecture notes, video lessons, and in-book quizzes (see [Section 4](#section-4-the-multimedia-book-mmb-chapters--sections)). |
| **Course Content**    | **Labs**                 | The laboratory section for practice coding problems and graded lab quizzes (see [Section 8](#section-8-labs-management--bulk-actions)).                                             |
| **Interactions**      | **Schedule**             | Displays the course calendar with scheduled activities, assignment deadlines, and lecture timings.                                                                                 |
| **Interactions**      | **Discussion Forum**     | The class discussion board where students post questions and instructors/TAs reply (see [Section 14.1](#141-class-discussion-forum)).                                               |
| **Interactions**      | **Email Notices**        | Send official email notices directly to all enrolled students' registered email inboxes.                                                                                           |
| **Interactions**      | **Course Announcements** | Post broadcast notices that display on students' course home screens (see [Section 14.2](#142-course-announcements)).                                                               |
| **Performance**       | **Grades**               | The complete gradebook table showing marks across all labs, coding tasks, and quizzes (see [Section 15.1](#151-grades-dashboard)).                                                  |
| **Performance**       | **Labs Performance**     | Detailed activity-wise performance statistics and completion percentages.                                                                                                          |
| **Performance**       | **Leaderboard**          | Shows student rankings based on points scored in practice activities.                                                                                                              |
| **Performance**       | **Statistics**           | Visual charts showing score distributions and class averages.                                                                                                                      |
| **Course Management** | **Settings**             | General course information, forum moderation settings, and content protection toggles (see [Section 13](#section-13-course-settings--content-protection)).                          |
| **Course Management** | **People**               | View enrolled students, invite teaching assistants, or upload a class list via CSV (see [Section 12](#section-12-people--student-enrollment)).                                      |
| **Additional Pages**  | **Add Page**             | Create custom markdown or rich-text web pages (e.g. Course Syllabus, Grading Policy, TA Office Hours).                                                                             |

---

## Section 4: The Multimedia Book (MMB): Chapters & Sections

The **Multimedia Book (MMB)** is the digital textbook of your course. You can organize your syllabus into **Chapters**, subdivide them into **Sections**, and add learning materials inside each section.

![Figure 6: Multimedia Book Overview](screenshots/fig_6_multimedia_book_overview.png)
*Figure 6: Multimedia Book Overview showing expanded chapter accordion and content items.*

---

### 4.1 Book Organization & Structure

As shown in **Figure 6**, the Multimedia Book displays your chapters in vertical sequence. Each chapter functions as an accordion card that expands to show its sections and contents.

---

### 4.2 Creating a New Chapter

To add a new chapter to your book:

1. Click the blue **+ Add Chapter** button at the top-right of the Multimedia Book (**Figure 6**).
2. The **Add Chapter** modal dialog opens, as shown in **Figure 7**.

![Figure 7: Add Chapter Modal](screenshots/fig_7_add_chapter_modal.png)
*Figure 7: Add Chapter Modal with Title, Description, and Save button.*

3. Enter the **Chapter Title** (e.g., `Chapter 1: Python Fundamentals`).
4. Enter an optional **Description** giving an overview of the chapter topics.
5. Click **Save**. The new chapter accordion appears in your book immediately.

---

### 4.3 Managing Chapters & Adding Sections

Once a chapter is created, you can manage it using the controls shown in **Figure 8**:

![Figure 8: Chapter Card and Content Controls](screenshots/fig_8_chapter_and_sections.png)
*Figure 8: Chapter Card showing header bar, Add Content button, and publish toggle.*

* **Expand / Collapse Accordion:** Click on the chapter header bar to reveal or hide the contents inside.
* **Chapter Menu (`⋮`):** Provides options to edit the chapter title/description or delete the chapter. When deleting a chapter, BodhiTree asks for a confirmation and permanently removes the chapter (chapters do not move to the Recycle Bin).
* **Publish / Eye Icon:** Click to toggle the chapter between Published (visible to enrolled students) and Unpublished (hidden from students).
* **+ Add Content Button:** Opens the menu to add learning materials inside this chapter.

---

## Section 5: Adding Learning Materials (Sections, In-Book Quizzes, Documents, Videos & URLs)

Inside any chapter, clicking the **+ Add Content** button opens the dropdown menu shown in **Figure 9**:

![Figure 9: Add Content Dropdown Menu](screenshots/fig_9_add_content_dropdown.png)
*Figure 9: Add Content Dropdown offering Section, Quiz, Document, Video, and URL options.*

---

### 5.1 The Add Content Menu

The dropdown provides five distinct content types in exact order:

1. **Section:** Group learning materials into clear topical sub-sections within the chapter.
2. **Quiz:** Add an interactive In-Book Quiz directly inside the chapter to test concepts while reading.
3. **Document:** Upload reading handouts and lecture slides for students (`.pdf`, `.txt`, and other document formats).
4. **Video:** Upload video lectures for students to watch.
5. **URL:** Link external web pages and reference documentation.

---

### 5.2 Adding a Section

Sections act as sub-folders inside a chapter to organize your topics cleanly:

1. Select **Section** from the dropdown (**Figure 9**).
2. In the popup dialog, enter the **Section Title** (e.g., `1.1 Variables and Assignment Statements`).
3. Enter an optional **Description** explaining the topics covered in this section.
4. Click **Save Section**. A new section card appears inside the chapter accordion where you can attach reading documents, videos, and quizzes.

---

### 5.3 Adding an In-Book Quiz

An **In-Book Quiz** is an interactive practice checkpoint placed directly inside a chapter or section. While students read through textbook chapters, they can solve questions on-screen to check their understanding right away:

1. Select **Quiz** from the dropdown (**Figure 9**).
2. The **Add Quiz** modal opens, as shown in **Figure 10**.

![Figure 10: Add Quiz Modal](screenshots/fig_10_add_quiz_modal.png)
*Figure 10: Add Quiz Modal showing Title, Description, Sample Files download, and Quiz File upload.*

3. Enter the **Quiz Title** (e.g., `Concept Check 1: Python Data Types`).
4. Enter an optional **Description** describing what the quiz covers.
5. **Sample Files:** Click the **Sample Files** dropdown button at the top-right of the modal to download reference templates (such as `.odt` or `.csv`) for offline authoring.
6. **Quiz File:** Optionally attach a quiz file (`.odt`, `.csv`, or `.txt`) using the drag-and-drop file upload area. If you prefer creating questions directly using the web interface, leave this empty.
7. Click **Save** to attach the quiz card inside your chapter.
8. Once created, click on the quiz card to open the **Quiz Editor** and add question modules and questions directly via the web UI (detailed in [Section 6](#section-6-the-multimedia-quiz-editor-generating-quizzes-via-ui)).

---

### 5.4 Adding a Document (File Attachments)

BodhiTree allows uploading reading handouts in multiple formats, including `.pdf`, `.txt`, and other text extensions:

1. Select **Document** from the dropdown (**Figure 9**).
2. The **Add Document** modal appears, as shown in **Figure 11**.

![Figure 11: Add Document Modal](screenshots/fig_11_add_document_modal.png)
*Figure 11: Add Document Modal with Title, Description, and Document File upload.*

3. Enter the **Document Title** (e.g., `Lecture 1 Notes - Variables & Expressions`).
4. Enter an optional **Description** giving a summary of the reading material.
5. Drag and drop or browse to select your **Document File** (`.pdf`, `.txt`, etc.) from your computer.
6. Click **Save** to attach the document.

---

### 5.5 Adding a Video Lecture

1. Select **Video** from the dropdown (**Figure 9**).
2. The **Add Video** modal appears, as shown in **Figure 12**.

![Figure 12: Add Video Modal](screenshots/fig_12_add_video_modal.png)
*Figure 12: Add Video Modal with Title, Description, Video File, Camtasia File, and Slides upload fields.*

3. Fill in the video details:
   * **Title:** Enter the title for the lecture (e.g., `Lecture 2: Python Functions and Scope`).
   * **Description:** Enter an optional description summarizing what this video lesson covers.
   * **Video File:** Drag and drop or browse your video recording (`.mp4`, `.webm`, `.avi`, `.mpeg`, or `.ogv`).
   * **Camtasia Config File:** If you recorded and edited your video using TechSmith Camtasia with chapters or markers, you can upload the exported `.xml` config file to import chapter timestamps automatically.
   * **Slides etc...:** Attach accompanying presentation slides (`.pdf`, `.pptx`, or documents) for students to follow along while watching.
4. Click **Save** to upload and attach the video lesson under your chapter.
5. Once uploaded, click on the video card to open the **Video Player Workspace** and add interactive timeline markers or in-video checkpoints (detailed in [Section 7](#section-7-in-video-quizzes--timeline-markers)).

---

### 5.6 Adding External Web URLs

1. Select **URL** from the dropdown (**Figure 9**).
2. The **Add URL** modal opens, as shown in **Figure 13**.

![Figure 13: Add URL Modal](screenshots/fig_13_add_url_modal.png)
*Figure 13: Add URL Modal with Title, Description, and URL fields.*

3. Fill in the resource details:
   * **Title:** Enter the resource title (e.g., `Python Standard Library Documentation`).
   * **Description:** Enter an optional description summarizing what students will find at this link.
   * **URL:** Enter the full web address (e.g., `https://docs.python.org/3/`). You can also click **+ Add Another URL** if you want to attach multiple links under a single card.
4. Click **Save**. When students click this card, the webpage opens in a clean inline frame or in a new browser tab.

---

## Section 6: The Multimedia Quiz Editor: Authoring Quizzes via UI

BodhiTree provides a built-in web-based **Quiz Editor** that lets instructors author interactive quizzes directly in their browser. You do not need to prepare complex spreadsheet templates or external files; you can create questions, set correct options, and configure marks using simple visual forms.

### 6.1 Purpose of the Quiz Editor

The Quiz Editor is used to author questions and provides a visual interface for:

* Grouping questions into structured modules.
* Adding questions across multiple formats (Single Choice, Multiple Choice, Numerical, and Descriptive).
* Setting marks/points, answer explanations, and student hints.
* Reordering, editing, and deleting questions directly on screen.

---

### 6.2 Organizing Questions with Modules

In BodhiTree, questions inside a quiz are grouped into **Modules**. A module represents a topic or subsection of the quiz (for example, "Module 1: Python Basics & Data Types" or "Module 2: Control Flow & Iteration").

![Figure 14: Quiz Editor Modules and Questions](screenshots/fig_14_mmb_quiz_modules.png)
*Figure 14: Quiz Editor showing question modules, question list, and action buttons.*

As shown in **Figure 14**, the Quiz Editor workspace provides:

* **Add Module Button:** Creates a new question module to group related questions by topic.
* **Add Question Button:** Opens the question builder modal to author a new question.
* **Reorder Button:** Switches the workspace into reorder mode so you can drag and drop modules and questions to rearrange their sequence.
* **Created Module Container:** Shows the module header (`Module 1: Python Basics & Data Types`), total question badge, visibility toggle, and nested questions.
* **Created Question Card:** Displays the question format badge (e.g. `MCQ`), question prompt (`Which format specifier is used for floating-point numbers in Python?`), and action controls.

---

### 6.3 Adding and Configuring Questions

To add a question to any module:

1. Click the blue **+ Add Question** button inside that module (**Figure 14**).
2. The **Add Question** modal dialog opens, as shown in **Figure 15**.

![Figure 15: Add Question Modal](screenshots/fig_15_mmb_add_question_modal.png)
*Figure 15: Add Question Modal showing Question Title (Description), Question Type, and Options.*

3. Configure the question details (**Figure 15**):
   * **Title:** Enter the title of your choice for the quiz question
   * **Description (Question):** Click the description box to enter the main question (e.g. problem statement, code snippet, etc.) that students will see.
   * **Question Type:** Select the question format from the dropdown:
     * **Multiple Choice (MCQ):** Questions with one or more correct choices.
     * **Single Choice (SCQ):** Questions with only a single correct option.
     * **Fixed Answer (FAQ):** Questions requiring an exact text answer match.
     * **Numerical Answer (FIB):** Questions where students enter a numerical value within an acceptable range.
   * **Options:** Click to type each choice's text, select the checkbox/radio button to mark correct answers, and click **+ Add Option** to add more answer choices.
   * **Marks & Attempts:** Set points awarded for correct submissions and the number of allowed attempts.
4. Click **Add Question** to save the new question into the module.

---

### 6.4 Understanding Hints, Answer Descriptions, and Error Descriptions

The interface also facilitates important feedback for the students :

* **Hints:** You can provide hints that students can open if they are stuck during practice.
* **Answer Description:** Enter a detailed solution explanation that students see after submitting their quiz, explaining why the correct choice is right.
* **Error Description:** Enter specific explanations to be displayed when a student selects an incorrect option, helping them understand where their reasoning went wrong.

---

## Section 7: In-Video Quizzes

In the **Multimedia Book**, instructors can embed interactive assessments directly inside lecture videos. This transforms passive lecture viewing into active learning by verifying comprehension at key points in the video.

### 7.1 Purpose of In-Video Quizzes

Unlike traditional quizzes that are attempted separately, **In-Video Quizzes** pause video playback automatically when a student reaches a designated timestamp. The student must answer the quiz before playback continues. This ensures students understand each concept before the lecture moves forward.

---

### 7.2 The Video Player Workspace

When you open an uploaded video lesson as an instructor, BodhiTree presents an interactive video player workspace with the **Chapters & Markers** toolbar located directly beneath the player screen:

![Figure 16: Video Player Workspace and Timeline Markers](screenshots/fig_16_in_video_quiz_player.png)
*Figure 16: Video Player Workspace showing the video screen with playback controls, Actions menu, and Chapters & Markers toolbar.*

As shown in **Figure 16**, the workspace provides:

* **Interactive Video Screen:** Displays the lecture video with on-hover playback controls (center play/pause, rewind/fast-forward, timeline seek bar with marker ticks, elapsed time, and volume).
* **Actions Menu Button:** Located at the top right of the video player, letting instructors switch to Student View, toggle bookmark visibility, and export/import quiz ODT files.
* **+ Add Marker/Quiz Button:** Placed on the Chapters & Markers header, enabling you to add a new Section or Quiz marker at the current timestamp.
* **Generated Section Marker:** Visual bookmark card (`SECTION 0:00 Introduction to Iteration`) indexing lecture topics for quick student navigation.
* **Generated Quiz Marker:** In-video assessment card (`QUIZ 0:05 Concept Check: While Loops`) that pauses playback at that exact second to test comprehension.

---

### 7.3 Section Markers vs. Quiz Markers

BodhiTree supports two types of timeline markers on video lectures:

1. **Section Marker (`S`):**
   * Acts as a named bookmark on the video progress bar (e.g., `0:00 - Introduction to Iteration`).
   * Indexes long lectures into topics so students can quickly jump to concepts without scrubbing.
2. **Quiz Marker (`Q`):**
   * Placed at an assessment timestamp (e.g., `0:05 - Concept Check: While Loops`).
   * Automatically pauses playback and displays an interactive assessment.
   * When setting up a Quiz Marker, BodhiTree gives you two creation paths:
     * **Add Question:** Creates a single question right at that timestamp.
     * **Add Module:** Links a whole question group/module containing multiple questions.

---

### 7.4 Adding, Editing, and Deleting Markers

Instructors can perform full management operations directly from the video workspace:

* **Adding Markers:** Play or scrub the video to your desired timestamp, then click **Add Marker/Quiz** above the timeline bar. Choose the marker type (`Section Marker` or `Quiz Marker`), enter the title, and save.
* **Editing Markers:** Click on any marker in the timeline bar. The inline **Edit Marker** panel opens directly below the video player, as shown in **Figure 17**:

![Figure 17: Inline Edit Marker Panel](screenshots/fig_17_in_video_quiz_editing.png)
*Figure 17: Inline Edit Marker Panel showing Update, Delete, and Cancel action buttons.*

* **Updating Content:** Inside the Edit Marker panel (**Figure 17**), modify the marker title in the input field and click the green **Update** button to save the new title immediately.
* **Deleting Markers:** Click the red **Delete** button at the top right of the panel to permanently remove the marker from the video timeline.
* **Canceling Edits:** Click the gray **Cancel** button to close the edit panel and return to the horizontal marker cards without making changes.

---

## Section 8: Labs Management & Bulk Actions

The **Labs** section is where instructors host hands-on programming activities and lab quizzes.

![Figure 18: Labs Dashboard](screenshots/fig_18_labs_dashboard.png)
*Figure 18: Labs Dashboard showing search filter, status tabs, and All Labs table.*

---

### 8.1 The Labs Dashboard

As shown in **Figure 18**, the Labs dashboard provides controls to organize all labs:

* **Search Bar & Filter Tabs:** Located at the top, allowing you to filter labs by typing titles or clicking filter tabs: **All Labs**, **Visible**, and **Hidden**.
* **Reorder Button:** Lets instructors drag and drop labs to rearrange their presentation order.
* **+ New Dropdown:** Located at the top-right, lets you create a new lab or import a lab package.
* **Labs Table Rows:** Each row displays:
  * **Title:** The name of the lab.
  * **Status:** Current visibility (Visible or Hidden).
  * **Timeline:** Availability date and time window.
  * **Submissions Count:** Number of student attempts received.
  * **Actions:** Quick links to edit, export, or manage activities.

---

### 8.2 Creating a New Lab

1. Click the **+ New** dropdown at the top-right (**Figure 18**) and choose **New Lab**.
2. The **Create Lab** modal opens, as shown in **Figure 19**.

![Figure 19: Create Lab Modal](screenshots/fig_19_create_lab_modal.png)
*Figure 19: Create Lab Modal showing Title, Instructions, Availability Dates, Submission Grace Period, and Action Buttons.*

3. Configure the lab parameters (**Figure 19**):
   * **Title:** Enter the lab name (e.g., `Lab 1: Python Basics Practice`).
   * **Instructions:** Detailed problem overview, objectives, and laboratory rules.
   * **Availability (Available From & Available Till):** The date and time window when the lab is open for student submissions.
   * **Submission Grace Period:** Specifies an extra buffer period (in HH:MM:SS) after the deadline during which students can still submit without being locked out.
   * **Preview as Student:** Click this button in the modal header to preview the student-facing view before saving.
   * **Submit:** Click the blue **Submit** button in the footer to create and save the lab.

---

### 8.3 Bulk Show & Hide Operations

When managing multiple labs across a semester, you do not need to publish them one by one. You can use bulk actions:

![Figure 20: Labs Bulk Action Bar](screenshots/fig_20_labs_bulk_actions.png)
*Figure 20: Labs List with multiple checkboxes selected and floating Bulk Action Bar at bottom.*

1. Check the selection checkbox next to one or more labs in the list (highlighted as **Selected Labs in Table** in **Figure 20**).
2. The floating **Bulk Action Bar** pops up at the bottom of the screen.
3. Click **Show** to publish all selected labs to students at once.
4. Click **Hide** to unpublish and hide the selected labs from students.

---

### 8.4 Inside a Lab: Activities, Editing, and Actions

Click on any lab title to open its detail page, shown in **Figure 21**:

![Figure 21: Lab Detail Page](screenshots/fig_21_lab_detail_page.png)
*Figure 21: Lab Detail Page highlighting the Activities Table, Create Activity dropdown, and Edit Icon with Action Button.*

The highlighted controls on this page include:

* **Edit Icon & Action Button:** Located at the top right next to the lab title. Click the **Edit** pencil icon to change the lab title, instructions, and availability dates. Click the **Action** button (`⋮` three-dot menu) to view the lab as a student, download submission CSVs, or export the lab archive.
* **Create Activity Dropdown:** Click this blue dropdown above the table to add a new **Programming Activity** (hands-on coding problem with automated test cases) or a **Quiz Activity** (lab quiz).
* **Activities Table:** Lists every activity in this lab with its name, activity type, submission count, student visibility toggle, and row action buttons (view submissions, edit, delete, or clone).
* **Submissions:** Click on submission icon in the Actions column to view all student submission attempts, check scores, and download reports (see [Section 11.1](#111-overall-lab-submissions--exporting-reports)).

---

## Section 9: Programming Activities & Autograding

A **Programming Activity** provides a hands-on coding environment. Students write and run code directly in their browser, and BodhiTree facilitates evaluation of their submissions against provided test cases.

![Figure 22: Create Programming Activity Form](screenshots/fig_22_programming_activity_editor.png)
*Figure 22: Create Programming Activity Form highlighting Title, Description, Files to be Submitted, and the Preview as Student button.*

---

### 9.1 What is a Programming Activity?

In a programming activity, students write code in an interactive code editor. When they click "Run Code", the platform executes their program inside a secure sandbox and checks the output against provided test cases.

---

### 9.2 Creating a Programming Activity: Basic Details & Setup

When creating a new programming activity (**Figure 22**), configure the primary settings in the **Basic Info** card:

1. **Title:** Enter a descriptive name for the activity (e.g., `Check Palindrome String` or `Matrix Multiplication`).
2. **Description:** Click inside the description box to open the editor and write clear problem instructions, expected inputs, outputs, and any constraints.
3. **Files to be Submitted:** Specify the expected submission file names without file extensions (e.g., `palindrome` , `matrix` , etc).
4. **Preview as Student:** Click the **Preview as Student** button in the top action bar to inspect how the problem statement and editor interface appear from a student's perspective before publishing.
5. **Language Selection & Solution:** Further down the page, choose the programming language (e.g., Python 3, C, C++, Java), provide template skeleton code for students, and enter the instructor reference solution.
6. **Helper Document:** Reference material or notes uploaded by the instructor that students can open for background assistance while solving the problem.

---

### 9.3 Configuring Test Cases: Visible vs. Hidden

Scroll down inside the programming activity editor to access the **Testcase Details** section, shown in **Figure 23**:

![Figure 23: Programming Activity Test Cases](screenshots/fig_23_programming_activity_testcases.png)
*Figure 23: Testcase Details section highlighting a Visible Testcase row, a Hidden Testcase row, + Add Testcase button, Reorder button, and the Actions menu.*

BodhiTree supports two types of test cases:

* **Visible Test Cases (Row 1):** Indicated with a green eye icon (`👁`). Students can see both the input given to the program and the expected output. These help students test and debug their code while working on the problem.
* **Hidden Test Cases (Row 2):** Indicated with a grey eye-off icon (`👁‍🗨`). Students cannot see the input or expected output. These test edge cases, large inputs, and boundary conditions so students cannot hardcode answers.

#### Testcase Management Controls & Actions

Instructors can configure and manage test cases using the following controls (**Figure 23**):

* **+ Add Testcase Button:** Located below the table. Click this button to add a new test case inline with its name, input data, expected output, visibility toggle, and assigned marks.
* **Reorder Button:** Located at the top right of the test case table. Opens a reorder modal allowing instructors to change the execution sequence of test cases.
* **Row Actions (Rightmost column in each row):**
  * **Edit (`✏` Pencil Icon):** Opens inline editing for the test case, allowing quick updates to its name, input, expected output, marks, or visibility toggle.
  * **Download (`⬇` Download Icon):** Downloads the specific test case input and output files to your local machine for verification.
  * **Delete (`🗑` Trash Icon):** Deletes the test case after a quick confirmation popup.
  * **Visibility Toggle (`👁` / `👁‍🗨` Eye Icon):** Click the eye icon in the Visibility column at any time to switch a test case between Visible and Hidden.
* **Actions Dropdown Menu (Top-Right):**
  * **Delete Selected:** Deletes all test cases currently selected via the row checkboxes.
  * **Bulk Upload Test Case:** Upload multiple test cases simultaneously using a `.zip` or `.tar.gz` archive.
  * **Configure Resource Limit:** Set custom execution timeouts (CPU time limit in seconds) and memory limits (MB) per test case run.
  * **Expose / Hide Hidden Testcases:** A single-click toggle to temporarily expose all hidden test cases to students (e.g., after an exam or assignment deadline for learning and review) or hide them again.
  * **Download All:** Downloads an archive containing all test cases configured for this programming activity.

---

### 9.4 Configure Resource Limits

To keep the platform responsive and prevent accidental infinite loops, configure resource limits:

* **CPU Time Limit:** Maximum execution time allowed per run (e.g., 2.0 seconds). If a student writes an infinite `while` loop, execution stops with a "Time Limit Exceeded" message.
* **Memory Limit:** Maximum RAM allocated per run (e.g., 256 MB) to prevent out-of-memory errors.

---

## Section 10: Lab Quizzes: Creation & Authoring

A **Lab Quiz** is a graded assessment activity housed inside a lab. It evaluates student performance as part of lab coursework alongside programming activities.

### 10.1 Important Difference: In-Book Quiz vs. Lab Quiz

| Feature                        | In-Book Quiz (In Multimedia Book)                                          | Lab Quiz (In Labs)                                                                                                 |
| :----------------------------- | :------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------- |
| **Location**             | Inside chapter reading view (see [Section 5.3](#53-adding-an-in-book-quiz)) | Inside Labs activity list (see [Section 8.4](#84-inside-a-lab-activities-editing-and-actions))                      |
| **Primary Goal**         | Self-paced practice with instant learning feedback                         | Graded lab assessment and evaluation                                                                               |
| **Timeline & Deadlines** | Available whenever the chapter is released, throughout the course period   | Governed by the parent Lab timeline (`Available From` / `Available Till`), identical to programming activities |
| **Resubmission Control** | Practice attempts                                                          | Configurable: **Allow students to resubmit until deadline**                                                  |
| **Score Visibility**     | Instant score and explanations displayed                                   | Configurable: **Allow students to see their marks on quiz submission**                                       |
| **Answer Revelation**    | Direct solution explanation provided                                       | Configurable: **Reveal correct answers to students**                                                         |
| **Feedback & Grading**   |                                                                            | Graded submissions dashboard with individual student answer sheets                                                 |

---

### 10.2 Creating a Lab Quiz Activity

To create a Lab Quiz:

1. Inside your lab (**Figure 21**), click **Create Activity** and choose **Quiz Activity**.
2. The Quiz Activity creation form opens, as shown in **Figure 24**:

![Figure 24: Quiz Activity Creation Form](screenshots/fig_24_lab_quiz_creation.png)
*Figure 24: Quiz Activity Creation Form highlighting Title, Description, and Question File (.odt format) upload with the Sample Question File button.*

3. Configure the primary fields and question upload settings (**Figure 24**):
   * **Title:** Enter the quiz activity name (e.g., `Midterm Lab Quiz: Python Basics`).
   * **Description:** Click inside the description box to enter student instructions, rules, or guidelines for the quiz.
   * **Question File (.odt format):**
     * Instructors can upload questions in bulk using an OpenDocument Text (`.odt`) file instead of manually typing each question one by one. You can prepare this `.odt` document offline using LibreOffice Writer, Google Docs (downloaded as `.odt`), or Microsoft Word (saved as `.odt`).
     * Click **Choose File** to select your `.odt` file. BodhiTree reads the document, parses the questions, answer options, marks, and solution keys, and adds them directly to the quiz.
     * **Sample Question File Button:** If you are creating a quiz for the first time, click the **Sample Question File** button next to the file picker. This downloads sample `.odt` files demonstrating the exact syntax and layout required (such as question headers, option bullets, and correct answer indicators). Use these sample files as a reference template to format your questions accurately.
   * **Quiz Settings:**
     * **Allow students to see their marks on quiz submission:** When enabled, students see their score immediately after submitting the quiz.
     * **Reveal correct answers to students:** When enabled, students can review which answers were correct after submission.
     * **Allow students to resubmit until deadline:** When enabled, students can update and resubmit their attempts as long as the parent lab is active.
     * **Additional Files:** Specify whether students must upload supplementary files (such as rough calculations or notes).
4. Click **Create Activity** to save the quiz.

---

### 10.3 Authoring Questions via Web UI Quiz Editor

Once a quiz activity is created, you can build and organize your questions directly using the web editor:

1. On the lab page, click on the quiz activity to open its view page.
2. Click **Edit** in the top action bar, then select **Edit Questions** to open the interactive **Question Management** page, shown in **Figure 25**:

![Figure 25: Lab Quiz Editor](screenshots/fig_25_lab_quiz_editor.png)
*Figure 25: Lab Quiz Editor showing the expanded Add Question/Module dropdown, generated modules, and generated questions.*

3. **Highlighted Elements in Figure 25:**
   * **Add Question/Module Menu:** Click this primary button in the top right to expand the creation menu. You can add a new module/group or pick any of the seven question types directly.
   * **Generated Module (Group):** Shows how questions are organized into clear sections (such as `Module 1: Python Basics & Syntax`). The header displays the category, total question count, total marks, and drag-and-drop reorder grip, along with edit and delete icons. Click the module header anytime to expand or collapse its questions.
   * **Generated Questions:** Displays questions populated inside the module. Each question card clearly shows its question number, question type badge, marks, negative marks, category, and full question statement.
4. **Question Types Supported in Web Editor:**
   * **Single Correct (SCQ):** Standard multiple choice question with one correct radio button option. You configure positive marks, negative marks, and the correct option.
   * **Multiple Correct (MCQ):** Questions where one or more checkboxes must be selected.
   * **Numerical:** Students enter a numeric value or answer within a specified range (min value to max value).
   * **Fill Blanks:** Sentence or code snippet with blanks. You can configure per-blank marks, negative marks, and multiple acceptable comma-separated answers.
   * **Descriptive/Paper:** Subjective or paper-based essay questions where students write long-form responses.
   * **Text:** Open-ended plain text explanation or short answer. Students type their response directly into a plain text area without formatting tools. Instructors evaluate these responses and assign marks manually.
   * **File Upload:** Asks students to submit an external file as their answer, such as a Python script (`.py`), C++ program, PDF report, or spreadsheet. BodhiTree stores the uploaded file with the student's submission record, allowing instructors to download and grade it directly.
5. For each question, specify the question statement, choices, points/marks, student hints, and answer descriptions.

---

## Section 11: Submissions Management & Student Evaluation

BodhiTree provides complete tools to inspect student code, view test case evaluations, grade quiz submissions, and export grade sheets.

---

### 11.1 Overall Lab Submissions & Exporting Reports

Access the lab submissions dashboard by clicking the **Submissions** icon against or inside any lab:

![Figure 26: Overall Lab Submissions Dashboard](screenshots/fig_26_lab_submissions.png)
*Figure 26: Overall Lab Submissions Dashboard showing the search filter, All Activities dropdown, View column toggler, Actions menu, and student submission grid.*

As shown in **Figure 26**, this dashboard gives instructors complete control over reviewing student progress across all activities in the lab:

1. **Top Metric Cards:** Quick summary cards displaying key figures at a glance—**Total Students** enrolled, **Submitted** attempts, **Evaluated** records, **Not Evaluated** records, and total **Activities** count.
2. **Search Bar:** Type any student name, roll number, or email (such as `example` to filter student accounts) to instantly filter the list. The table updates live without reloading the page.
3. **Controls in Figure 26:**
   * **All Activities:** Use this dropdown to select particular activities to show as columns in the table. You can view all activities together or filter down to a single programming task or quiz (such as *Quiz 1*, *Quiz 2*, or *Addition of two number*).
   * **View (Toggle Columns):** Click **View** to choose which columns to add or remove from the table view. You can toggle checkboxes for *Name*, *Email*, *Roll No*, *Updated On*, *Activities Submitted*, and individual activity scores. This helps you hide extra columns when you only want to focus on marks.
   * **Actions:** Use this dropdown for exporting student work:
     * **Download Selected Submissions:** Downloads submitted code and uploaded files for only the students you select using the row checkboxes.
     * **Download as CSV:** Exports the whole lab marksheet across all students and activities as a spreadsheet (`.csv`) file for your records or institutional grading.
4. **Student Submissions Table:** Displays student rows with serial number, email, name, roll number, latest submission timestamp, number of activities submitted, and individual scores for each quiz and programming activity (showing auto-evaluation marks, manual marks, and rubric marks). Status badges indicate whether an exercise is *Not Attempted*, *Not Submitted*, or evaluated.
5. **Pagination:** Easily navigate through large classes using the page controls at the bottom of the table.

---

### 11.2 Programming Submissions & Subjective Grading

To review student code for a specific programming problem:

1. Open the programming activity and click the **Submissions** icon to open the programming submissions dashboard, shown in **Figure 27**:

![Figure 27: Programming Activity Submissions](screenshots/fig_27_programming_submissions.png)
*Figure 27: Programming Activity Submissions dashboard showing the Run, Force Run, More, Filters, and View action controls.*

2. **Highlighted Action Controls in Figure 27:**
   * **Run:** Triggers automated evaluation for pending student submissions. Click this dropdown to select which testcases to execute:
     * **Visible Testcases:** Evaluates code against practice testcases that students can see.
     * **Hidden Testcases:** Evaluates code against private testcases reserved for grading.
     * **All Testcases:** Evaluates code against both visible and hidden testcases together.
   * **Force Run:** Re-evaluates student submissions even if they were evaluated earlier. It provides the same three options—**Visible Testcases**, **Hidden Testcases**, and **All Testcases**. Use Force Run when you update a testcase, change execution time limits, or fix a reference solution, ensuring all student submissions get re-graded with the latest test settings.
   * **More:** Provides administrative, export, and evaluation utilities grouped into clear categories:
     * **Download & Export:**
       * **Download All Submissions:** Downloads a ZIP archive containing all student code files.
       * **Download as CSV:** Exports a complete spreadsheet (`.csv`) containing roll numbers, emails, timestamps, testcase scores, and total marks.
       * **Deposit Data:** Archives and deposits submission files into course storage.
     * **Submit:**
       * **Bulk Submission:** Allows instructors to upload student solution archives in bulk on behalf of students.
     * **Plagiarism Check:**
       * **New Plagiarism Request:** Sends student files to BodhiTree's code similarity engine.
       * **Show Plagiarism Results:** Displays similarity percentages, match matrices, and side-by-side code comparisons.
     * **TA Management:**
       * **Create Grading Request:** Distributes student submissions among Teaching Assistants for manual grading.
       * **Show Grading Requests:** Tracks TA evaluation progress and completed reviews.
   * **Filters:** Quickly filter the submission list using dropdown filters:
     * **Submission Status:** Show *All* or only *Submitted* students.
     * **Evaluation Status:** Filter by *All*, *Pending*, or *Evaluated*.
     * **Rubric Status:** Filter by *All*, *Graded*, or *Not Graded*.
     * **Validity:** Filter by *All* or *Invalid* submissions.
   * **View (Toggle Columns):** Customize which columns appear in the table. You can toggle checkboxes for *Roll No*, *Email*, *Name*, *Uploaded On*, *Evaluated On*, *File Submitted*, *TA*, *Graded By*, *Graded On*, *Testcases*, *Total Practice Marks*, *Total Evaluate Marks*, *Grade*, *Rubrics Marks*, *Manual Marks*, *Execution Time*, *Indentation Percentage*, and *Submission Status*.
3. Click on the **Grade** button next to any student to open the detailed subjective grading workspace, shown in **Figure 28**:

![Figure 28: Programming Grading Page](screenshots/fig_28_programming_grading_page.png)
*Figure 28: Subjective Grading Workspace showing code viewer, manual marks override, Run/View testcase controls, and student feedback comments.*

4. **Highlighted Grading Tools in Figure 28:**
   * **Code Viewer (Left Pane):** Displays the student's submitted code (e.g., `Sum.c`) with syntax highlighting, line numbers, and indentation. Instructors can inspect the code structure and logic directly.
   * **Manual Marks (Score Override):** The numeric input box next to *Manual Marks* lets you adjust or override the automated score manually. Enter the desired score and click the green checkmark button to save it, or click the cancel button to revert. This allows you to award partial credit for good logic or apply manual penalties.
   * **Run:** Re-executes the student's code against testcases in real time directly from the grading view. You can verify how the student's code runs without leaving the page.
   * **View:** Opens the testcase results inspector. It shows individual testcase execution status, standard output, expected output diffs, and execution times.
   * **Comments & Feedback:** Use the comment box at the bottom-right to write personalized feedback, code reviews, or improvement notes. The student can read these comments when checking their evaluated submission.
   * **Student Switcher:** The *Select Student* dropdown at the top-right lets you quickly jump between students without returning to the main submissions table.

---

### 11.3 Lab Quiz Submissions & Individual Grading

To inspect quiz attempts, download student files, and grade submissions:

1. Open the quiz activity and click **Submissions** to open the **Quiz Submissions Dashboard**, shown in **Figure 29**:

![Figure 29: Lab Quiz Submissions Dashboard](screenshots/fig_29_lab_quiz_submissions.png)
*Figure 29: Lab Quiz Submissions Dashboard showing summary metrics, View and Actions menus, and the full submissions table.*

2. **Top Summary & Controls in Figure 29:**
   * **Summary Cards & Search Bar:** Shows live counts for **Total Students** and **Total Submissions** (with a refresh button to update numbers) along with a search bar to filter students by name, email, or roll number.
   * **View (Toggle Columns):** Click **View** to open the column toggle menu (*TOGGLE COLUMNS*). Use **Select All** or individual checkboxes to show or hide optional columns in the table:
     * **Roll No:** Displays the student's roll number.
     * **TA:** Shows the Teaching Assistant assigned to that student.
     * **Submitted On:** Shows the date and time when the student submitted.
     * **Graded On:** Shows when the submission was graded.
   * **Actions:** Click **Actions** to export class data in bulk:
     * **Download Marks:** Exports a CSV spreadsheet containing question-wise marks and total scores for all students.
     * **Download All Files:** Downloads a compressed `.tar.gz` archive containing all uploaded files submitted by students across file-upload or descriptive questions.
3. **Submissions Table Columns & Row Actions:**
   * **Sorting & Status:** Click column headers like **Email**, **Name**, **Marks**, **Total Marks**, or **Submission Status** to sort students. Status pills show whether an attempt is *Submitted*, *Incomplete*, or *Not Uploaded*.
   * **Download Files:** Click **Download Files** in any student's row to download a `.tar.gz` archive of only that student's uploaded answer files. If the student has not submitted anything yet, a warning notice appears.
   * **View Submission:** Click **View Submission** to open that student's complete answer sheet in a new tab for question-by-question review and manual grading, shown in **Figure 30**.
   * **Delete Submission:** Click the trash icon in the rightmost column to delete a student's submission after confirmation (for example, to clear an incomplete test attempt so the student can retake the quiz).

![Figure 30: Quiz Grading Page](screenshots/fig_30_quiz_grading_page.png)
*Figure 30: Quiz Grading Page showing the Switch Student dropdown, Grade button for manual questions, and the Manual Grading status panel.*

4. **Highlighted Grading Controls & Details in Figure 30:**
   * **Switch Student Dropdown (Top Right):** Click the *Student:* dropdown to open the full class list along with each student's submission status (such as *Incomplete*, *Submitted*, or *Not Uploaded*). Select any student to jump straight to their grading view without returning to the submissions table.
   * **How to Grade using the Grade Button:** Auto-graded questions (Numeric, Single/Multiple Choice, Fill Blanks) score automatically, and clicking **Answer** reveals the correct solution key and explanation. For **File Upload**, **Text**, or **Descriptive/Paper** questions, scroll down to the question and click the green **Grade** button:
     * An inline **Grade Question** panel opens inside the card.
     * Enter the score in **Marks (out of total marks)** and optionally write feedback in **Remarks / Comments** (up to 255 characters).
     * Click **Save** to record the grade. After saving, the card updates **Scored Marks** and shows evaluation details (*Submitted on*, *Graded by*, and *Graded on*).
   * **Manual Grading Panel (Right Sidebar):** Located beneath the **Questions** navigator (green circles mark attempted questions), this panel gives a quick summary of every manually graded question and updates right after evaluation:
     * **Id & Type:** Shows the question sequence number and format (*Subjective*, *Text*, or *File Upload*).
     * **TA & Graded On:** Displays who graded the answer and the evaluation timestamp.
     * **Status:** Switches from *Not Graded* to a green **graded** pill once marks are saved.
     * **Marks:** Displays the final awarded manual score (e.g., `3`).

---

## Section 12: People & Student Enrollment

The **People** page (`/courseware/course/<id>/management/people`) lets instructors manage course participants, assign roles, track bulk imports, and handle enrollment.

![Figure 31: People Management Dashboard](screenshots/fig_31_people_management.png)
*Figure 31: People Management Dashboard showing summary cards, Enroll Students/TAs, Import History, Actions menu, and the Enrolled Users table.*

---

### 12.1 The People Dashboard

As shown in **Figure 31**, the People dashboard organizes participant management across four sections:

1. **Summary Cards & Tabs:**
   * Top cards show live counts for **Total Students**, **Approved**, **Pending Approval**, and **Current TAs**.
   * Switch between three tabs: **Approved Students** (currently enrolled learners), **Pending Approvals** (students waiting for approval), and **Current TAs** (instructors, STAs, and JTAs).
2. **Highlighted Top Action Controls in Figure 31:**
   * **Search Bar:** Live search box (`Search by name or email...`) to find enrolled students quickly.
   * **Enroll Students/TAs:** Opens the enrollment dialog to add individual users (existing or new) or import students in bulk from CSV/Excel files.
   * **Import History:** Opens an import audit window listing past bulk CSV enrollment uploads along with timestamps, import status (`SUCCESS`, `PARTIAL`, or `FAILED`), expandable per-row details, and a button to download the original CSV file.
   * **Actions Dropdown:** Click **Actions** for bulk utilities affecting selected rows or filtered students:
     * **Send Password Reset Email:** Sends password reset links in bulk to selected students.
     * **Send Onboarding Email:** Sends welcome/onboarding login emails to selected students.
     * **Send Email to Inactive Students:** Opens a dialog to email students who have not yet activated or joined course activity.
     * **Export All / Active / Inactive Students:** Downloads a `.csv` file matching your current filter (*All*, *Active*, or *Inactive*), including names, emails, roll numbers, and batch tags.
     * **Upload Tags:** Uploads a `.csv` file to update roll numbers or add custom batch/section columns (such as lab group or section) in bulk.
     * **Edit Tags / Save Tags:** Switches table cells (*Roll No.* and batch tag columns) into inline text boxes so you can edit values directly or remove custom columns (`×`). Click **Save Tags** in Actions to store updates.
     * **Change Role:** Promotes selected students to **STA** (Senior TA) or **JTA** (Junior TA).
     * **Deregister:** Removes selected students (or all matching students when using *Select all*) from the course after confirmation.
3. **Filters & Enrolled Users Table (Highlighted):**
   * **Activity Filter & Counters:** Filter between **All**, **Active**, and **Inactive** students. To the right, counters display `Selected: X` and `Showing Y of Z Students`.
   * **Checkboxes & Multi-Page Selection:** Check individual students or click the top checkbox to select everyone loaded on screen. When additional pages exist, a top banner lets you click **Select all N students** or **Clear selection**.
   * **Table Columns:** Displays **Full Name**, **Email**, **Roll No.** (inline editable via *Edit Tags*), **Role** (e.g., `STUDENT`), and any custom **Batch/Tag** columns added via CSV upload.
   * **Load More:** If more than 100 students exist in the course, a **Load More** button appears at the bottom of the table to fetch remaining records.

---

### 12.2 Single User Enrollment (New User & Existing User Search)

Clicking the blue **Enroll Students/TAs** button opens the **Enroll Students/TAs** modal shown in **Figure 32**. Everything you need to add users—whether uploading a spreadsheet or enrolling people one by one—is available right here in two side-by-side panels:

![Figure 32: Enroll Students/TAs Modal](screenshots/fig_32_add_user_modal.png)
*Figure 32: Enroll Students/TAs modal showing the Bulk File Upload panel on the left, and the + Add and Search and Add Students/TAs options on the right.*

Here is what each highlighted section does:

1. **File Upload Enroll (`Bulk File based Students Upload` panel on the left):**
   Use this panel when adding a full class or batch using a `.csv` file (explained step by step in **Section 12.3** below):
   * **Select CSV File (`Choose File`):** Pick a `.csv` file from your computer containing student or TA details.
   * **Is it an ASC file?:** Tick this checkbox if your CSV file comes directly from an institutional ASC export so BodhiTree parses its format properly.
   * **Send welcome or password reset email?:** Checked by default so newly created users receive their login/onboarding email automatically.
   * **Sample CSV:** Click this link to download `sample-csv-download.csv` as a ready-to-use template.
   * **Role (`STA` / `JTA` / `Student`):** Choose which role everyone in the uploaded CSV will receive (`Student` is selected by default).
   * **Enroll:** Starts the upload. BodhiTree validates your rows, shows a review/confirmation screen if needed (for new accounts, existing portal users, already-enrolled users, or new columns/profile updates), tracks the import, and displays the final enrollment summary.

2. **`+ Add` Button (Create & Enroll a New User):**
   Use **`+ Add`** in the right panel (`Add Individual Students/TAs`) to enroll one person directly without a CSV file. Clicking it opens a simple form with:
   * **Name \*:** Full name of the user (required).
   * **Email \*:** Valid email address for the account (required).
   * **Roll No.:** Institutional roll number or ID (optional).
   * **Role:** Pick **STA**, **JTA**, or **Student** (defaults to **Student**).
   * **Batch Tags:** Any extra batch tag fields appear here automatically if configured for the course.
   * **Send onboarding email to user:** Checked by default to email login details to the user.
   * Click **Add** to enroll the user immediately, or **Back** to return to the two-panel modal.

3. **`Search and Add Students/TAs` Button (Enroll Existing Portal Users):**
   Use **`Search and Add Students/TAs`** when the students or TAs already have accounts on BodhiTree:
   * First select the **Role** you want to assign (**Student**, or **TA** -> **STA** / **JTA**).
   * Type a name or email into **Search existing users by Name/Email...** and click **Search** (or **Clear** to reset).
   * Tick the checkboxes next to the users you want in the results table (**NAME**, **EMAIL**, **ROLL NO.**) and click **Add N User(s)** to enroll them.
   * If a matching user is already in the course, BodhiTree shows them as already enrolled with a **Change to \<Role\>** option so you can switch their role directly.

---

### 12.3 Bulk CSV Student Upload

For classes with dozens or hundreds of students, use the bulk CSV upload tool inside the enrollment modal:

1. On the **People** page, click **Enroll Students/TAs** to open the modal (**Figure 32**) and look at the **Bulk File based Students Upload** panel on the left.
2. Click **Sample CSV** if you want a template, or prepare a standard `.csv` file in your spreadsheet app with these headers:
   ```csv
   email,roll_number,name
   student1@example.com,210050001,Aarav Sharma
   student2@example.com,210050002,Diya Patel
   student3@example.com,210050003,Rohan Verma
   ```
3. Click **Choose File** to select your `.csv` file.
4. Tick **Is it an ASC file?** if it is an ASC export, keep **Send welcome or password reset email?** checked if you want users notified, and pick the **Role** (**STA**, **JTA**, or **Student**).
5. Click **Enroll**. BodhiTree creates accounts for any new users, enrolls existing ones into the course, updates roll numbers/names if confirmed, and shows the final count once done.

---

### 12.4 Course Roles: Students, TAs (STA / JTA), and Instructors

BodhiTree provides fine-grained role separation:

| Role                      | Access Permissions                                                                     | Primary Responsibilities                                                          |
| :------------------------ | :------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------- |
| **Student**         | Read published content, submit code/quizzes, post on forums                            | Attending lectures, completing lab exercises, and participating in discussions    |
| **Junior TA (JTA)** | Grade submissions, view student code, assist in lab sessions                           | Grading lab activities, answering student questions on discussion forums          |
| **Senior TA (STA)** | Create/edit lab activities, moderate forums, view gradebook, grade submissions         | Managing lab schedules, configuring test cases, supervising JTAs                  |
| **Instructor**      | Full course administrative control: add/delete materials, edit settings, manage grades | Course design, lecture uploads, setting grading policies, and final grade exports |

---

## Section 13: Course Settings & Content Protection

Access course settings by clicking **Settings** under **Course Management** in the left sidebar (`/courseware/course/<id>/management/settings`).

![Figure 33: Course Settings Top Half](screenshots/fig_33_course_settings_top.png)
*Figure 33: Course Settings showing Title (course code), Full Title, Enrollment Type, Institute, Department, and Course Image upload.*

---

### 13.1 General Course Settings

At the top of the **Course Settings** card, BodhiTree displays who created the course and when (`Course created by` / `Created at`). Below that, you can configure the highlighted settings (**Figure 33**):

* **Title (Course Code):** Enter the short course code shown alongside the course name (for example, `MAIN101`). It supports up to 8 alphanumeric or `-` characters and saves in uppercase.
* **Full Title (Course Name):** Enter or update the full display title of your course (for example, `Main Automation Testing`).
* **Enrollment Type (Enrollment Mode):** Switch between **Open** (anyone can enroll directly) and **Moderated** (students submit an admission request for instructor/TA approval).
* **Institute & Department:** Select the host **Institute** (`IIT Bombay`) and **Department** (`Computer Science and Engineering`) from the dropdown menus.
* **Course Image:** Click **Upload** on the right panel to pick an image and adjust the crop area for the course card thumbnail. Once uploaded, **Change Image**, **Edit Crop**, and **Remove** options become available.

Scroll slightly down to click the blue **Update** button to save these changes. Right below the **Course Settings** card, the **About Course** section lets you click **Edit** to write or update the course description and syllabus in a rich-text editor.

---

### 13.2 Multimedia Book Settings

Scroll down past **About Course** to reach the **Multimedia Book Settings** card, shown in **Figure 34**:

![Figure 34: Multimedia Book Settings](screenshots/fig_34_course_settings_bottom.png)
*Figure 34: Multimedia Book Settings highlighting the Course Home option, Quiz feedback toggles, Course Content Prefix input, and Save button.*

Use the highlighted controls in this section to customize how the Multimedia Book behaves for students:

* **Course Content (`Course Content as course home page for students`):** Tick this box to make the Multimedia Book content list the default home page whenever students open your course.
* **Quiz Feedback Options:**
  * **Reveal Answer Response as Right or Wrong:** Immediately tells students whether their submitted answer in an in-book quiz is right or wrong.
  * **Reveal Correct Answer:** Displays the right answer after a student submits an in-book quiz.
* **Prefix for Course Content:** Type a custom prefix (up to 50 characters, such as `Chapter`, `Week`, `Day`, or `Module`) to appear before each item's number in the course content list (for example, `"Chapter 1. Title"`).
* **Save:** Click the blue **Save** button at the bottom-right of the card to apply your Multimedia Book settings.

---

### 13.3 Discussion Forum Settings

Further down the settings page (right below **Course Announcement Settings**, where eligible courses can turn on **Emails sent to all students on every announcement**), you will find the **Discussion Forum Settings** card with two checkboxes:

* **Emails sent to all students on every post:** Turn this on if you want every enrolled student to receive an email notification whenever a new post is added on the Discussion Forum.
* **Reveal identity of anonymous posts to Instructor/TAs:** Keeps student identities hidden from classmates on anonymous posts while still letting instructors and TAs see who wrote the post.

Click **Save** at the bottom-right of the card after updating your choices.

---

### 13.4 Content Protection

At the bottom of Course Settings (visible to the **course creator**), the **Enable Content Protection** toggle prevents accidental deletions by other staff:

* When enabled, only the course creator can delete chapters, sections, labs, or learning elements. Other instructors and TAs will not see delete options.
* Turning Content Protection off opens a confirmation dialog warning that **Instructors** and **Senior Teaching Assistants (STAs)** will be allowed to delete course content.

---

## Section 14: Interactions: Discussion Forums & Announcements

BodhiTree includes integrated communication tools so instructors and students do not need external messaging groups.

### 14.1 Class Discussion Forum

Access the forum by clicking **Discussion Forum** under **INTERACTIONS** in the left sidebar (`/courseware/course/<id>/interactions/discussion-forum`):

![Figure 35: Discussion Forum](screenshots/fig_35_discussion_forum.png)
*Figure 35: Course Discussion Forum highlighting the + Create Thread button and a generated instructor thread.*

* **+ Create Thread Button:** Click the blue **+ Create Thread** button (highlighted at the top right in **Figure 35**) to start a new discussion topic. It opens the **Create New Thread** pop-up with the following controls:
  * **Write / Preview Tabs:** Switch between **Write** to type your post and **Preview** to see how your formatted text will look before posting.
  * **Thread Title & Description:** Enter a clear **Thread Title** and write the details in the rich-text **Description** editor.
  * **Tags:** Optionally attach topic tags so students can quickly tell what chapter or lab the thread is about (when tags are added, they appear on the thread card with a `+` button to add more).
  * **Thread Options:** Tick **Pin this thread to the top** to keep key announcements visible above regular posts, **Mark as important** to highlight urgent updates, or **Post anonymously** to hide your name from students (instructors and TAs can still see the real author if the setting in **Section 13.3** is enabled).
  * Click **Create Thread** at the bottom of the pop-up to publish the post (or **Cancel** to discard it).
* **Generated Thread Card:** Published posts appear in the thread feed below the filter bar (**Figure 35** shows a pinned and important instructor post titled *Clarification on Lab 1 Recursion Base Case & Submission Deadline*):
  * **Author & Status Badges:** Shows the author's initials, name, role badge (such as **INSTRUCTOR**, **TA**, **STA**, **JTA**, or student), and posting date and time. Pinned posts carry a blue pin icon, and important posts carry a yellow warning icon along with an orange border on the left.
  * **Content & Three-Dot Menu (`...`):** Displays the message body (or a **Read more / Show less** toggle for longer posts). Click the **`...`** menu in the top-right corner of the card to **Edit**, **Delete**, **Pin Content / Unpin Content**, or **Mark as Important / Unmark Important**. Instructors and TAs can delete any thread to moderate the forum, while only the original author can edit a thread.
  * **Likes, Replies & Views:** At the bottom of each card, users can click the thumbs-up icon to upvote (**Like**) a helpful thread, click the **replies** count (for example, `1 reply`) to open or close the comments section, and check the **views** count.
* **Comments & Nested Replies:** Clicking the **replies** button opens the comment editor below the thread. Anyone can write a rich-text comment, tick **Post anonymously** if needed, upvote comments, or click **Reply** on an existing comment to start a nested reply. Authors can delete their own comments, and instructors or TAs can **Pin / Unpin** helpful comments or delete inappropriate ones.
* **Search & Filter Tabs:** Use the **Search discussions...** box at the top to find threads by keyword, or switch between **Recent**, **Earlier**, **Popularity**, **Importance**, and **Instructor** tabs to sort posts and focus on popular, important, or instructor-posted threads.

---

### 14.2 Course Announcements

Access announcements by clicking **Course Announcements** under **INTERACTIONS** in the left sidebar (`/courseware/course/<id>/interactions/announcements`):

![Figure 36: Course Announcements Board](screenshots/fig_36_course_announcements.png)
*Figure 36: Course Announcements board highlighting the + New Announcement button and a generated announcement card.*

* **+ New Announcement Button:** Click the blue **+ New Announcement** button (highlighted at the top right in **Figure 36**) to open the **Create New Announcement** pop-up:
  * **Step 1 — Write Announcement:** Enter an **Announcement Title**, click the **Content (Click to edit)** box to open the rich-text editor and type your message, then click **Preview** (or **Cancel** to discard).
  * **Step 2 — Preview & Email Check:** Before publishing, BodhiTree shows **How students will see this** along with an email status banner. Depending on your **Course Announcement Settings** (and course plan or student enrollment), it either shows how many students will receive an email (`Publishing will email N students`, with a sample recipient list) or tells you that email notifications are off and the post will appear on the course page only. Click **Back to edit** to make changes, or click **Publish Announcement** to post it.
  * **Background Email Progress:** When email notifications are enabled, an **Email Sending Status** card automatically appears above the list so you can track **Sent**, **Failed**, and **Pending** counts even if you move to another page.
* **Generated Announcement Card:** Each published notice appears under **All Announcements** (or under **Pinned Announcements** at the top when pinned), as highlighted in **Figure 36**:
  * **Header Badges & Timestamp:** Displays the author's initials, name, role badge (**Instructor** or **Staff**), a blue **New** badge for announcements posted within the last 7 days, and the publish date and time.
  * **Title & Message Body:** Shows the announcement title and formatted message (longer notices over 300 characters automatically get a **Read more / Show less** toggle).
  * **Card Actions (Pin, Edit, Delete):** Use the three icons on the top right of the card to **Pin / Unpin** important notices to the **Pinned Announcements** section at the top, **Edit** the title or content (updating an announcement does not re-send emails), or **Delete** the announcement after confirmation.
* **Search & Date Filters:** Use **Search announcements by title, content, or author...** to quickly find past notices, or click **Filters** to filter announcements by **From Date** and **To Date**.

---

## Section 15: Performance Tracking & Gradebook

The **Grades** dashboard (`/courseware/course/<id>/performance/grades`) gathers student scores across all course activities into one view.

![Figure 37: Performance & Gradebook Grid](screenshots/fig_37_grades_performance.png)
*Figure 37: Gradebook Grid showing student scores across all lab exercises and quizzes.*

---

### 15.1 Grades Dashboard

As shown in **Figure 37**, the gradebook displays:

* Rows for each student with their Roll Number and Name.
* Columns for every lab exercise, programming problem, and quiz.
* Summary statistics at the bottom showing Highest Score, Class Average, and Submission Count.

---

### 15.2 Exporting Grades to CSV

At the end of the semester, click the **Export CSV** button on the top-right of the gradebook. BodhiTree downloads an Excel-compatible spreadsheet containing all student marks, ready for institutional grading.

---

## Section 16: Recycle Bin & Common Troubleshooting

### 16.1 Restoring Deleted Items from Recycle Bin

If you accidentally delete a lab or programming activity, you can recover or permanently remove it from the **Recycle Bin** (`/courseware/course/<id>/content/labs/recyclebin`). Open **Labs** from the left sidebar and click **Recycle Bin** (use the **Labs / Recycle Bin** breadcrumb at the top to return anytime):

![Figure 38: Recycle Bin](screenshots/fig_38_recycle_bin.png)
*Figure 38: Recycle Bin highlighting the Actions dropdown button and a deleted item row with Restore and Delete Permanently controls.*

* **Deleted Item Row (`NAME`, `TYPE`, `ACTIONS`):** Each row in the table (one example row is highlighted in **Figure 38**) lists the item's **Name** (click the blue link to view its details) and **Type** (`Lab` or `Program`), along with two per-row action icons under **ACTIONS**:
  * **Restore (Green Arrow Icon):** Click the green restore icon on the row to open the **Restore Item?** confirmation pop-up, then click **Restore**. The lab or programming activity goes back to its original place with all student submissions intact. If an item cannot be restored yet (for instance, its parent lab is still in the bin), BodhiTree shows a **Cannot Restore Item** message explaining the issue.
  * **Delete Permanently (Red Trash Icon):** Click the red trash icon to open the **Delete Permanently?** warning pop-up (*"This action cannot be undone."*). Clicking **Delete** removes the item permanently. *(If **Enable Content Protection** in **Section 13.4** is turned on, only the course creator sees permanent delete options.)*
* **Actions Dropdown Button (Bulk Actions):** Click the **Actions** button (highlighted at the top right in **Figure 38**) to act on the entire Recycle Bin at once:
  * **Restore All:** Restores every item in the Recycle Bin back to the course after confirmation (**Restore All Items?**).
  * **Delete All:** Permanently clears all items from the Recycle Bin after confirmation (**Delete All Items Permanently?**). *(Hidden for non-creator staff when **Content Protection** is enabled.)*
* **Pagination:** When there are more than 10 deleted items, page buttons (**Prev** / **Next**) appear at the bottom of the table.

---

### 16.2 Common Issues & Quick Solutions

| Issue                                                          | Likely Cause                                               | How to Fix                                                                                                                                                   |
| :------------------------------------------------------------- | :--------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Students cannot find the course on Explore page**      | Course is marked as Unpublished on the dashboard           | Click the green Publish button on the course card ([Section 2.1](#21-the-my-courses-dashboard)). Enrolled students can still access it directly.              |
| **Students cannot see a chapter, video, or lab**         | Item is currently Unpublished (Draft mode)                 | Open the chapter or lab and click the eye / publish icon to make it visible to students ([Section 4.3](#43-managing-chapters--adding-sections)).              |
| **Code submission gives "Time Limit Exceeded"**          | The student's code contains an infinite loop               | Ask the student to check their loop termination conditions, or increase the CPU time limit in activity settings ([Section 9.4](#94-setting-resource-limits)). |
| **Need to re-evaluate quiz after correcting answer key** | Questions or marks were modified after student submissions | Open the Lab Quiz Submissions page and click the **Force Run** button ([Section 11.3](#113-lab-quiz-submissions--individual-grading)).                  |
| **Another instructor or STA cannot see delete options**       | Content Protection is turned on by the course creator      | Open Course Settings and turn off **Enable Content Protection** if staff deletion access is needed ([Section 13.4](#134-content-protection)).             |

---

*End of BodhiTree Product Manual & Instructor Guide.*
