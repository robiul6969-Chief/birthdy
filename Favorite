<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Academic Platform</title>

  <style>
    *{
      box-sizing:border-box;
      margin:0;
      padding:0;
    }

    body{
      font-family:Arial,"Noto Sans Bengali",sans-serif;
      background:#f4f7fb;
      color:#172033;
    }

    button,input,select,textarea{
      font:inherit;
    }

    button{
      cursor:pointer;
    }

    .hidden{
      display:none!important;
    }

    /* HEADER */

    header{
      background:#102a63;
      color:white;
      padding:16px 6%;
      display:flex;
      justify-content:space-between;
      align-items:center;
      position:sticky;
      top:0;
      z-index:100;
      box-shadow:0 3px 15px #0002;
    }

    .brand{
      font-size:22px;
      font-weight:700;
    }

    nav{
      display:flex;
      gap:20px;
    }

    nav button{
      background:none;
      border:0;
      color:white;
      padding:6px;
    }

    /* HOME */

    .hero{
      background:white;
      text-align:center;
      padding:85px 20px;
    }

    .hero h1{
      font-size:43px;
      margin-bottom:15px;
    }

    .hero p{
      color:#667085;
      font-size:18px;
      line-height:1.6;
    }

    .actions{
      margin-top:30px;
    }

    .btn{
      border:0;
      border-radius:9px;
      padding:13px 20px;
      margin:5px;
      transition:.2s;
    }

    .btn:hover{
      transform:translateY(-2px);
    }

    .primary{
      background:#1746a2;
      color:white;
    }

    .secondary{
      background:#eaf0ff;
      color:#1746a2;
    }

    .danger{
      background:#dc3545;
      color:white;
    }

    .success{
      background:#198754;
      color:white;
    }

    /* CARDS */

    .cards{
      max-width:1200px;
      margin:auto;
      padding:50px 20px;
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
      gap:20px;
    }

    .card{
      background:white;
      padding:28px 22px;
      border-radius:15px;
      text-align:center;
      box-shadow:0 5px 22px #0000000d;
    }

    .card h3{
      margin-bottom:12px;
    }

    .card p{
      color:#667085;
      line-height:1.6;
    }

    /* FORMS */

    .page{
      max-width:1100px;
      margin:40px auto;
      padding:20px;
    }

    .form-box{
      max-width:620px;
      margin:auto;
      background:white;
      padding:30px;
      border-radius:16px;
      box-shadow:0 5px 25px #00000012;
    }

    .form-box h2{
      text-align:center;
      margin-bottom:22px;
    }

    input,select,textarea{
      width:100%;
      padding:13px;
      margin:7px 0;
      border:1px solid #d9dee8;
      border-radius:8px;
      outline:none;
      background:white;
    }

    textarea{
      min-height:110px;
      resize:vertical;
    }

    input:focus,
    select:focus,
    textarea:focus{
      border-color:#1746a2;
    }

    .message{
      text-align:center;
      margin-top:12px;
      line-height:1.5;
    }

    /* ADMIN */

    .dashboard-header{
      background:white;
      padding:25px;
      border-radius:15px;
      box-shadow:0 5px 20px #0001;
      margin-bottom:20px;
    }

    .dashboard-header h2{
      margin-bottom:7px;
    }

    .dashboard-header p{
      color:#667085;
    }

    .admin-menu{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(170px,1fr));
      gap:12px;
      margin-bottom:25px;
    }

    .admin-menu button{
      border:0;
      background:white;
      padding:18px 10px;
      border-radius:12px;
      box-shadow:0 4px 15px #0000000d;
      cursor:pointer;
    }

    .admin-menu button:hover{
      background:#eef3ff;
    }

    .admin-section{
      background:white;
      padding:25px;
      border-radius:15px;
      box-shadow:0 5px 20px #0000000d;
      margin-bottom:20px;
    }

    .admin-section h3{
      margin-bottom:18px;
    }

    .data-item{
      border:1px solid #e4e7ec;
      padding:15px;
      border-radius:10px;
      margin:10px 0;
      background:#fafbfc;
    }

    .data-item strong{
      display:block;
      margin-bottom:5px;
    }

    .small-btn{
      border:0;
      padding:8px 12px;
      border-radius:7px;
      margin:3px;
      cursor:pointer;
    }

    /* FOOTER */

    footer{
      background:#111827;
      color:white;
      text-align:center;
      padding:30px 20px;
      margin-top:30px;
    }

    .developer{
      margin-top:10px;
      color:#cbd5e1;
      font-size:14px;
    }

    .developer strong{
      color:white;
    }

    /* MOBILE */

    @media(max-width:700px){

      header{
        padding:15px 20px;
      }

      nav{
        display:none;
      }

      .hero{
        padding:60px 18px;
      }

      .hero h1{
        font-size:31px;
      }

      .hero p{
        font-size:16px;
      }

      .page{
        padding:15px;
      }

      .form-box{
        padding:22px;
      }
    }
  </style>
</head>

<body>

<!-- HEADER -->

<header>

  <div class="brand">
    🎓 Academic Platform
  </div>

  <nav>
    <button onclick="showHome()">Home</button>
    <button onclick="showPublic('noticePage')">Notice</button>
    <button onclick="showPublic('resultPage')">Result</button>
  </nav>

</header>


<!-- HOME -->

<main id="homePage">

  <section class="hero">

    <h1>এক প্ল্যাটফর্মে সব Academic Services</h1>

    <p>
      School • Madrasah • College — সবার জন্য একটি আধুনিক
      Academic Management Platform
    </p>

    <div class="actions">

      <button
        class="btn primary"
        onclick="openPage('institutionLoginPage')">
        🏫 Institution Login
      </button>

      <button
        class="btn secondary"
        onclick="openPage('studentLoginPage')">
        👨‍🎓 Student Login
      </button>

      <button
        class="btn primary"
        onclick="openPage('registerPage')">
        ➕ Register Institution
      </button>

    </div>

  </section>


  <section class="cards">

    <div class="card">
      <h3>📢 Notice</h3>
      <p>প্রতিষ্ঠানের গুরুত্বপূর্ণ নোটিশ দেখুন।</p>

      <button
        class="btn secondary"
        onclick="showPublic('noticePage')">
        Open
      </button>
    </div>


    <div class="card">
      <h3>📊 Result</h3>
      <p>পরীক্ষার ফলাফল দেখুন।</p>

      <button
        class="btn secondary"
        onclick="showPublic('resultPage')">
        Open
      </button>
    </div>


    <div class="card">
      <h3>📝 Routine</h3>
      <p>পরীক্ষার রুটিন দেখুন।</p>

      <button
        class="btn secondary"
        onclick="showPublic('routinePage')">
        Open
      </button>
    </div>


    <div class="card">
      <h3>📚 Study Materials</h3>
      <p>নোট ও পড়াশোনার উপকরণ দেখুন।</p>

      <button
        class="btn secondary"
        onclick="showPublic('materialsPage')">
        Open
      </button>
    </div>

  </section>

</main>


<!-- INSTITUTION REGISTRATION -->

<section id="registerPage" class="page hidden">

  <div class="form-box">

    <h2>🏫 Register Your Institution</h2>

    <input
      id="regInstitutionName"
      placeholder="প্রতিষ্ঠানের নাম">

    <select id="regInstitutionType">

      <option value="">
        প্রতিষ্ঠানের ধরন নির্বাচন করুন
      </option>

      <option value="School">School</option>
      <option value="Madrasah">Madrasah</option>
      <option value="College">College</option>

    </select>

    <input
      id="regAdminName"
      placeholder="Admin নাম">

    <input
      id="regEmail"
      type="email"
      placeholder="Admin Email">

    <input
      id="regPassword"
      type="password"
      placeholder="Password — কমপক্ষে ৬ অক্ষর">

    <button
      class="btn primary"
      onclick="registerInstitution()">
      Create Institution
    </button>

    <button
      class="btn secondary"
      onclick="showHome()">
      Back Home
    </button>

    <div
      id="registerMessage"
      class="message">
    </div>

  </div>

</section>


<!-- INSTITUTION LOGIN -->

<section id="institutionLoginPage" class="page hidden">

  <div class="form-box">

    <h2>🔐 Institution Admin Login</h2>

    <input
      id="loginEmail"
      type="email"
      placeholder="Admin Email">

    <input
      id="loginPassword"
      type="password"
      placeholder="Password">

    <button
      class="btn primary"
      onclick="institutionLogin()">
      Login
    </button>

    <button
      class="btn secondary"
      onclick="openPage('registerPage')">
      Register Institution
    </button>

    <button
      class="btn secondary"
      onclick="showHome()">
      Back Home
    </button>

    <div
      id="loginMessage"
      class="message">
    </div>

  </div>

</section>


<!-- STUDENT LOGIN -->

<section id="studentLoginPage" class="page hidden">

  <div class="form-box">

    <h2>👨‍🎓 Student Login</h2>

    <input
      id="studentEmail"
      type="email"
      placeholder="Student Email">

    <input
      id="studentPassword"
      type="password"
      placeholder="Password">

    <button
      class="btn primary"
      onclick="studentLogin()">
      Login
    </button>

    <button
      class="btn secondary"
      onclick="showHome()">
      Back Home
    </button>

    <div
      id="studentMessage"
      class="message">
    </div>

  </div>

</section>


<!-- ADMIN PANEL -->

<section id="adminPanel" class="page hidden">

  <div class="dashboard-header">

    <h2>🏫 Institution Admin Panel</h2>

    <p id="adminInstitutionName">
      Loading...
    </p>

  </div>


  <div class="admin-menu">

    <button onclick="adminSection('adminDashboard')">
      📊 Dashboard
    </button>

    <button onclick="adminSection('studentManagement')">
      👨‍🎓 Students
    </button>

    <button onclick="adminSection('noticeManagement')">
      📢 Notices
    </button>

    <button onclick="adminSection('resultManagement')">
      📊 Results
    </button>

    <button onclick="adminSection('routineManagement')">
      📝 Routine
    </button>

    <button onclick="adminSection('materialManagement')">
      📚 Materials
    </button>

    <button onclick="adminSection('teacherManagement')">
      👨‍🏫 Teachers
    </button>

    <button onclick="adminSection('institutionSettings')">
      ⚙️ Institution
    </button>

    <button onclick="logout()">
      🚪 Logout
    </button>

  </div>


  <!-- DASHBOARD -->

  <div
    id="adminDashboard"
    class="admin-section">

    <h3>📊 Dashboard</h3>

    <p>
      আপনার Academic Platform Administration Dashboard।
    </p>

    <div id="dashboardInfo"></div>

  </div>


  <!-- STUDENTS -->

  <div
    id="studentManagement"
    class="admin-section hidden">

    <h3>👨‍🎓 Student Management</h3>

    <input
      id="newStudentName"
      placeholder="Student Name">

    <input
      id="newStudentEmail"
      type="email"
      placeholder="Student Email">

    <input
      id="newStudentId"
      placeholder="Student ID">

    <input
      id="newStudentClass"
      placeholder="Class">

    <input
      id="newStudentRoll"
      placeholder="Roll">

    <input
      id="newStudentPassword"
      type="password"
      placeholder="Temporary Password">

    <button
      class="btn primary"
      onclick="createStudent()">
      ➕ Add Student
    </button>

    <div id="studentList"></div>

  </div>


  <!-- NOTICES -->

  <div
    id="noticeManagement"
    class="admin-section hidden">

    <h3>📢 Notice Management</h3>

    <input
      id="noticeTitle"
      placeholder="Notice Title">

    <textarea
      id="noticeText"
      placeholder="Notice Details"></textarea>

    <button
      class="btn primary"
      onclick="addNotice()">
      ➕ Publish Notice
    </button>

    <div id="noticeList"></div>

  </div>


  <!-- RESULTS -->

  <div
    id="resultManagement"
    class="admin-section hidden">

    <h3>📊 Result Management</h3>

    <input
      id="resultStudentId"
      placeholder="Student ID">

    <input
      id="resultExam"
      placeholder="Exam Name">

    <input
      id="resultSubject"
      placeholder="Subject">

    <input
      id="resultMarks"
      type="number"
      placeholder="Marks">

    <button
      class="btn primary"
      onclick="addResult()">
      ➕ Add Result
    </button>

    <div id="resultList"></div>

  </div>


  <!-- ROUTINE -->

  <div
    id="routineManagement"
    class="admin-section hidden">

    <h3>📝 Exam Routine</h3>

    <input
      id="routineExam"
      placeholder="Exam Name">

    <input
      id="routineDate"
      type="date">

    <input
      id="routineSubject"
      placeholder="Subject">

    <input
      id="routineTime"
      placeholder="Time">

    <button
      class="btn primary"
      onclick="addRoutine()">
      ➕ Add Routine
    </button>

    <div id="routineList"></div>

  </div>


  <!-- MATERIALS -->

  <div
    id="materialManagement"
    class="admin-section hidden">

    <h3>📚 Study Materials</h3>

    <input
      id="materialTitle"
      placeholder="Material Title">

    <input
      id="materialUrl"
      placeholder="PDF / Material Link">

    <button
      class="btn primary"
      onclick="addMaterial()">
      ➕ Add Material
    </button>

    <div id="materialList"></div>

  </div>


  <!-- TEACHERS -->

  <div
    id="teacherManagement"
    class="admin-section hidden">

    <h3>👨‍🏫 Teacher Management</h3>

    <input
      id="teacherName"
      placeholder="Teacher Name">

    <input
      id="teacherSubject"
      placeholder="Subject">

    <input
      id="teacherPhone"
      placeholder="Phone">

    <button
      class="btn primary"
      onclick="addTeacher()">
      ➕ Add Teacher
    </button>

    <div id="teacherList"></div>

  </div>


  <!-- INSTITUTION SETTINGS -->

  <div
    id="institutionSettings"
    class="admin-section hidden">

    <h3>⚙️ Institution Settings</h3>

    <p id="settingsInfo">
      Institution information will appear here.
    </p>

  </div>

</section>


<!-- PUBLIC NOTICE -->

<section
  id="noticePage"
  class="page hidden">

  <div class="form-box">

    <h2>📢 Notices</h2>

    <div id="publicNoticeList">
      No notices available.
    </div>

    <button
      class="btn secondary"
      onclick="showHome()">
      Back Home
    </button>

  </div>

</section>


<!-- PUBLIC RESULT -->

<section
  id="resultPage"
  class="page hidden">

  <div class="form-box">

    <h2>📊 Results</h2>

    <p>
      Student login করার পরে নিজের result দেখতে পারবে।
    </p>

    <button
      class="btn secondary"
      onclick="showHome()">
      Back Home
    </button>

  </div>

</section>


<!-- PUBLIC ROUTINE -->

<section
  id="routinePage"
  class="page hidden">

  <div class="form-box">

    <h2>📝 Exam Routine</h2>

    <div id="publicRoutineList">
      No routine available.
    </div>

    <button
      class="btn secondary"
      onclick="showHome()">
      Back Home
    </button>

  </div>

</section>


<!-- PUBLIC MATERIALS -->

<section
  id="materialsPage"
  class="page hidden">

  <div class="form-box">

    <h2>📚 Study Materials</h2>

    <div id="publicMaterialList">
      No materials available.
    </div>

    <button
      class="btn secondary"
      onclick="showHome()">
      Back Home
    </button>

  </div>

</section>


<!-- FOOTER -->

<footer>

  <div>
    © 2026 Academic Platform
  </div>

  <div class="developer">
    Developed by
    <strong>MD ROBIUL ISLAM</strong>
  </div>

</footer>


<!-- FIREBASE -->

<script type="module">

  import {
    initializeApp,
    getApps
  } from
  "https://www.gstatic.com/firebasejs/12.1.0/firebase-app.js";


  import {
    getAuth,
    createUserWithEmailAndPassword,
    signInWithEmailAndPassword,
    signOut
  } from
  "https://www.gstatic.com/firebasejs/12.1.0/firebase-auth.js";


  import {
    getFirestore,
    doc,
    getDoc,
    setDoc,
    addDoc,
    collection,
    query,
    where,
    getDocs,
    deleteDoc,
    serverTimestamp
  } from
  "https://www.gstatic.com/firebasejs/12.1.0/firebase-firestore.js";


  /* FIREBASE CONFIG */

  const firebaseConfig = {

    apiKey:
      "AIzaSyBSaL_bQAgGMGhyEGW7ClPSLj0mKDrhZJw",

    authDomain:
      "academic-platform-0320.firebaseapp.com",

    projectId:
      "academic-platform-0320",

    storageBucket:
      "academic-platform-0320.firebasestorage.app",

    messagingSenderId:
      "845941845419",

    appId:
      "1:845941845419:web:7fb594950013d5c996b6ee",

    measurementId:
      "G-BJXTZCPV5Z"

  };


  /* MAIN FIREBASE APP */

  const app =
    initializeApp(firebaseConfig);

  const auth =
    getAuth(app);

  const db =
    getFirestore(app);


  let currentInstitution = null;


  /* PAGE FUNCTIONS */

  window.openPage = function(id){

    document
      .getElementById("homePage")
      .classList.add("hidden");

    document
      .querySelectorAll(".page")
      .forEach(p =>
        p.classList.add("hidden")
      );

    document
      .getElementById(id)
      .classList.remove("hidden");

    window.scrollTo(0,0);
  };


  window.showHome = function(){

    document
      .querySelectorAll(".page")
      .forEach(p =>
        p.classList.add("hidden")
      );

    document
      .getElementById("homePage")
      .classList.remove("hidden");

    window.scrollTo(0,0);
  };


  window.showPublic = function(id){

    openPage(id);

    if(id === "noticePage")
      loadPublicNotices();

    if(id === "routinePage")
      loadPublicRoutines();

    if(id === "materialsPage")
      loadPublicMaterials();

  };


  /* ADMIN SECTION */

  window.adminSection = function(id){

    document
      .querySelectorAll(".admin-section")
      .forEach(section =>
        section.classList.add("hidden")
      );

    document
      .getElementById(id)
      .classList.remove("hidden");

    if(id === "studentManagement")
      loadStudents();

    if(id === "noticeManagement")
      loadNotices();

    if(id === "resultManagement")
      loadResults();

    if(id === "routineManagement")
      loadRoutines();

    if(id === "materialManagement")
      loadMaterials();

    if(id === "teacherManagement")
      loadTeachers();

  };


  /* REGISTER INSTITUTION */

  window.registerInstitution =
  async function(){

    const name =
      document
      .getElementById("regInstitutionName")
      .value.trim();

    const type =
      document
      .getElementById("regInstitutionType")
      .value;

    const adminName =
      document
      .getElementById("regAdminName")
      .value.trim();

    const email =
      document
      .getElementById("regEmail")
      .value.trim();

    const password =
      document
      .getElementById("regPassword")
      .value;

    const message =
      document
      .getElementById("registerMessage");


    if(!name || !type ||
       !adminName || !email ||
       !password){

      message.textContent =
        "❌ সব তথ্য পূরণ করুন।";

      return;
    }


    if(password.length < 6){

      message.textContent =
        "❌ Password কমপক্ষে ৬ অক্ষরের হতে হবে।";

      return;
    }


    message.textContent =
      "⏳ Registration হচ্ছে...";


    try{

      const result =
        await createUserWithEmailAndPassword(
          auth,
          email,
          password
        );


      const uid =
        result.user.uid;


      await setDoc(
        doc(db,"institutions",uid),
        {

          institutionName:name,

          institutionType:type,

          adminName:adminName,

          adminEmail:email,

          ownerUid:uid,

          createdAt:
            serverTimestamp()

        }
      );


      message.textContent =
        "✅ Institution সফলভাবে তৈরি হয়েছে! এখন Login করুন।";


    }catch(error){

      console.error(error);

      message.textContent =
        "❌ Registration হয়নি: " +
        error.message;

    }

  };


  /* ADMIN LOGIN */

  window.institutionLogin =
  async function(){

    const email =
      document
      .getElementById("loginEmail")
      .value.trim();

    const password =
      document
      .getElementById("loginPassword")
      .value;

    const message =
      document
      .getElementById("loginMessage");


    if(!email || !password){

      message.textContent =
        "❌ Email এবং Password দিন।";

      return;
    }


    message.textContent =
      "⏳ Login হচ্ছে...";


    try{

      const result =
        await signInWithEmailAndPassword(
          auth,
          email,
          password
        );


      const uid =
        result.user.uid;


      const institutionDoc =
        await getDoc(
          doc(db,"institutions",uid)
        );


      if(!institutionDoc.exists()){

        message.textContent =
          "❌ Institution profile পাওয়া যায়নি।";

        return;
      }


      currentInstitution =
        institutionDoc.data();


      document
        .getElementById(
          "adminInstitutionName"
        )
        .textContent =
        currentInstitution.institutionName;


      document
        .getElementById("dashboardInfo")
        .innerHTML =
        "<p>Welcome, <strong>" +
        currentInstitution.adminName +
        "</strong></p>";


      openPage("adminPanel");


      adminSection("adminDashboard");


    }catch(error){

      console.error(error);

      message.textContent =
        "❌ Login হয়নি: " +
        error.message;

    }

  };


  /* STUDENT LOGIN */

  window.studentLogin =
  async function(){

    const email =
      document
      .getElementById("studentEmail")
      .value.trim();

    const password =
      document
      .getElementById("studentPassword")
      .value;

    const message =
      document
      .getElementById("studentMessage");


    if(!email || !password){

      message.textContent =
        "❌ Email এবং Password দিন।";

      return;
    }


    try{

      await signInWithEmailAndPassword(
        auth,
        email,
        password
      );


      message.textContent =
        "✅ Student Login সফল হয়েছে।";

    }catch(error){

      message.textContent =
        "❌ Login হয়নি: " +
        error.message;

    }

  };


  /* CREATE STUDENT */

  window.createStudent =
  async function(){

    if(!currentInstitution){

      alert("Admin Login প্রয়োজন।");
      return;

    }


    const name =
      document
      .getElementById("newStudentName")
      .value.trim();

    const email =
      document
      .getElementById("newStudentEmail")
      .value.trim();

    const studentId =
      document
      .getElementById("newStudentId")
      .value.trim();

    const studentClass =
      document
      .getElementById("newStudentClass")
      .value.trim();

    const roll =
      document
      .getElementById("newStudentRoll")
      .value.trim();

    const password =
      document
      .getElementById("newStudentPassword")
      .value;


    if(!name || !email ||
       !studentId || !password){

      alert("Student-এর প্রয়োজনীয় তথ্য পূরণ করুন।");
      return;

    }


    /*
      Student account creation needs a secondary
      Firebase authentication app.
    */

    try{

      const secondaryName =
        "studentCreatorApp";


      let secondaryApp;


      const existing =
        getApps().find(
          a => a.name === secondaryName
        );


      if(existing){

        secondaryApp = existing;

      }else{

        secondaryApp =
          initializeApp(
            firebaseConfig,
            secondaryName
          );

      }


      const {
        getAuth: getSecondaryAuth,
        createUserWithEmailAndPassword:
          createSecondaryUser
      } =
      await import(
        "https://www.gstatic.com/firebasejs/12.1.0/firebase-auth.js"
      );


      const secondaryAuth =
        getSecondaryAuth(secondaryApp);


      const studentCredential =
        await createSecondaryUser(
          secondaryAuth,
          email,
          password
        );


      const studentUid =
        studentCredential.user.uid;


      await setDoc(
        doc(db,"students",studentUid),
        {

          studentName:name,

          studentEmail:email,

          studentId:studentId,

          studentClass:studentClass,

          roll:roll,

          institutionOwnerUid:
            currentInstitution.ownerUid,

          createdAt:
            serverTimestamp()

        }
      );


      alert(
        "✅ Student account তৈরি হয়েছে।"
      );


      document
      .getElementById("newStudentName")
      .value="";

      document
      .getElementById("newStudentEmail")
      .value="";

      document
      .getElementById("newStudentId")
      .value="";

      document
      .getElementById("newStudentClass")
      .value="";

      document
      .getElementById("newStudentRoll")
      .value="";

      document
      .getElementById("newStudentPassword")
      .value="";


      loadStudents();


    }catch(error){

      console.error(error);

      alert(
        "❌ Student তৈরি হয়নি: " +
        error.message
      );

    }

  };


  /* NOTICE */

  window.addNotice =
  async function(){

    if(!currentInstitution) return;


    const title =
      document
      .getElementById("noticeTitle")
      .value.trim();

    const text =
      document
      .getElementById("noticeText")
      .value.trim();


    if(!title || !text){

      alert("Notice-এর তথ্য দিন.");
      return;

    }


    await addDoc(
      collection(db,"notices"),
      {

        title:title,

        text:text,

        institutionOwnerUid:
          currentInstitution.ownerUid,

        createdAt:
          serverTimestamp()

      }
    );


    document
      .getElementById("noticeTitle")
      .value="";

    document
      .getElementById("noticeText")
      .value="";


    loadNotices();

  };


  /* RESULT */

  window.addResult =
  async function(){

    if(!currentInstitution) return;


    const studentId =
      document
      .getElementById("resultStudentId")
      .value.trim();

    const exam =
      document
      .getElementById("resultExam")
      .value.trim();

    const subject =
      document
      .getElementById("resultSubject")
      .value.trim();

    const marks =
      document
      .getElementById("resultMarks")
      .value;


    if(!studentId || !exam ||
       !subject || marks === ""){

      alert("সব Result তথ্য দিন.");
      return;

    }


    await addDoc(
      collection(db,"results"),
      {

        studentId:studentId,

        exam:exam,

        subject:subject,

        marks:Number(marks),

        institutionOwnerUid:
          currentInstitution.ownerUid,

        createdAt:
          serverTimestamp()

      }
    );


    document
      .getElementById("resultStudentId")
      .value="";

    document
      .getElementById("resultExam")
      .value="";

    document
      .getElementById("resultSubject")
      .value="";

    document
      .getElementById("resultMarks")
      .value="";


    loadResults();

  };


  /* ROUTINE */

  window.addRoutine =
  async function(){

    if(!currentInstitution) return;


    const exam =
      document
      .getElementById("routineExam")
      .value.trim();

    const date =
      document
      .getElementById("routineDate")
      .value;

    const subject =
      document
      .getElementById("routineSubject")
      .value.trim();

    const time =
      document
      .getElementById("routineTime")
      .value.trim();


    if(!exam || !date ||
       !subject || !time){

      alert("Routine-এর সব তথ্য দিন.");
      return;

    }


    await addDoc(
      collection(db,"routines"),
      {

        exam:exam,

        date:date,

        subject:subject,

        time:time,

        institutionOwnerUid:
          currentInstitution.ownerUid,

        createdAt:
          serverTimestamp()

      }
    );


    loadRoutines();

  };


  /* MATERIAL */

  window.addMaterial =
  async function(){

    if(!currentInstitution) return;


    const title =
      document
      .getElementById("materialTitle")
      .value.trim();

    const url =
      document
      .getElementById("materialUrl")
      .value.trim();


    if(!title || !url){

      alert("Material title এবং link দিন.");
      return;

    }


    await addDoc(
      collection(db,"materials"),
      {

        title:title,

        url:url,

        institutionOwnerUid:
          currentInstitution.ownerUid,

        createdAt:
          serverTimestamp()

      }
    );


    loadMaterials();

  };


  /* TEACHER */

  window.addTeacher =
  async function(){

    if(!currentInstitution) return;


    const name =
      document
      .getElementById("teacherName")
      .value.trim();

    const subject =
      document
      .getElementById("teacherSubject")
      .value.trim();

    const phone =
      document
      .getElementById("teacherPhone")
      .value.trim();


    if(!name || !subject){

      alert("Teacher name এবং subject দিন.");
      return;

    }


    await addDoc(
      collection(db,"teachers"),
      {

        name:name,

        subject:subject,

        phone:phone,

        institutionOwnerUid:
          currentInstitution.ownerUid,

        createdAt:
          serverTimestamp()

      }
    );


    loadTeachers();

  };


  /* GENERIC LOADER */

  async function loadCollection(
    collectionName,
    elementId,
    formatter
  ){

    if(!currentInstitution) return;


    const q =
      query(
        collection(db,collectionName),
        where(
          "institutionOwnerUid",
          "==",
          currentInstitution.ownerUid
        )
      );


    const snapshot =
      await getDocs(q);


    const container =
      document.getElementById(elementId);


    container.innerHTML="";


    if(snapshot.empty){

      container.innerHTML =
        "<p>No data available.</p>";

      return;

    }


    snapshot.forEach(item => {

      const div =
        document.createElement("div");

      div.className="data-item";

      div.innerHTML =
        formatter(
          item.data(),
          item.id
        );

      container.appendChild(div);

    });

  }


  /* LOAD STUDENTS */

  async function loadStudents(){

    loadCollection(
      "students",
      "studentList",
      (data,id) => `

        <strong>
          ${escapeHTML(data.studentName || "")}
        </strong>

        Student ID:
        ${escapeHTML(data.studentId || "")}

        <br>

        Class:
        ${escapeHTML(data.studentClass || "")}

        <br>

        Roll:
        ${escapeHTML(data.roll || "")}

      `
    );

  }


  /* LOAD NOTICES */

  async function loadNotices(){

    loadCollection(
      "notices",
      "noticeList",
      (data,id) => `

        <strong>
          ${escapeHTML(data.title || "")}
        </strong>

        ${escapeHTML(data.text || "")}

      `
    );

  }


  /* LOAD RESULTS */

  async function loadResults(){

    loadCollection(
      "results",
      "resultList",
      (data,id) => `

        <strong>
          ${escapeHTML(data.exam || "")}
        </strong>

        Student ID:
        ${escapeHTML(data.studentId || "")}

        <br>

        Subject:
        ${escapeHTML(data.subject || "")}

        <br>

        Marks:
        ${escapeHTML(String(data.marks ?? ""))}

      `
    );

  }


  /* LOAD ROUTINES */

  async function loadRoutines(){

    loadCollection(
      "routines",
      "routineList",
      (data,id) => `

        <strong>
          ${escapeHTML(data.exam || "")}
        </strong>

        ${escapeHTML(data.date || "")}
        —
        ${escapeHTML(data.time || "")}

        <br>

        Subject:
        ${escapeHTML(data.subject || "")}

      `
    );

  }


  /* LOAD MATERIALS */

  async function loadMaterials(){

    loadCollection(
      "materials",
      "materialList",
      (data,id) => `

        <strong>
          ${escapeHTML(data.title || "")}
        </strong>

        <a
          href="${escapeAttribute(data.url || "#")}"
          target="_blank"
          rel="noopener">
          Open Material
        </a>

      `
    );

  }


  /* LOAD TEACHERS */

  async function loadTeachers(){

    loadCollection(
      "teachers",
      "teacherList",
      (data,id) => `

        <strong>
          ${escapeHTML(data.name || "")}
        </strong>

        Subject:
        ${escapeHTML(data.subject || "")}

        <br>

        Phone:
        ${escapeHTML(data.phone || "")}

      `
    );

  }


  /* PUBLIC DATA */

  async function loadPublicNotices(){

    document
      .getElementById("publicNoticeList")
      .innerHTML =
      "<p>Public notice system will show institution notices here.</p>";

  }


  async function loadPublicRoutines(){

    document
      .getElementById("publicRoutineList")
      .innerHTML =
      "<p>Routine will appear here after institution selection.</p>";

  }


  async function loadPublicMaterials(){

    document
      .getElementById("publicMaterialList")
      .innerHTML =
      "<p>Study materials will appear here.</p>";

  }


  /* LOGOUT */

  window.logout =
  async function(){

    await signOut(auth);

    currentInstitution=null;

    showHome();

  };


  /* BASIC HTML SAFETY */

  function escapeHTML(value){

    return String(value)
      .replaceAll("&","&amp;")
      .replaceAll("<","&lt;")
      .replaceAll(">","&gt;")
      .replaceAll('"',"&quot;")
      .replaceAll("'","&#039;");

  }


  function escapeAttribute(value){

    return String(value)
      .replaceAll('"',"&quot;")
      .replaceAll("'","&#039;");

  }

</script>

</body>
</html>
