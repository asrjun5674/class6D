<
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>St. Michael's Academy Gandhinagar — Class 6D</title>
  <style>
    :root{--accent:#0b6e4f;--muted:#556;--card:#fff;--bg:#f5f7fb}
    *{box-sizing:border-box}body{font-family:Inter, system-ui, Arial, Helvetica, sans-serif;margin:0;background:var(--bg);color:#111}
    header{background:linear-gradient(90deg,var(--accent),#117a61);color:#fff;padding:18px 22px}
    .container{max-width:980px;margin:20px auto;padding:18px}
    .top{display:flex;gap:18px;align-items:center}
    .brand{flex:1;display:flex;align-items:center;gap:12px}
    .brand img{width:55px;height:auto;border-radius:8px;background:#fff;padding:4px}
    h1{font-size:20px;margin:0 0 4px}
    .meta{font-size:14px;opacity:.95}

    .grid{display:grid;grid-template-columns:1fr 320px;gap:18px;margin-top:18px}
    .card{background:var(--card);padding:14px;border-radius:10px;box-shadow:0 6px 18px rgba(10,20,30,0.06)}

    .ann h3{margin:0 0 8px}
    .ann p{margin:6px 0}

    .students{max-height:320px;overflow:auto}
    .student{display:flex;align-items:center;gap:12px;padding:8px;border-radius:8px;border:1px solid #f0f0f0;margin-bottom:8px}
    .avatar{width:44px;height:44px;border-radius:50%;background:#e9f6f1;display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent)}

    table{width:100%;border-collapse:collapse}
    th,td{padding:10px;border-bottom:1px solid #eee;text-align:left;font-size:14px}
    th{background:#fafafa}

    label{display:block;font-size:13px;margin-top:8px}
    input[type=text],select,textarea{width:100%;padding:8px;margin-top:6px;border-radius:6px;border:1px solid #ddd}
    button{background:var(--accent);color:#fff;padding:10px 12px;border:0;border-radius:8px;cursor:pointer;margin-top:10px}
    button.secondary{background:#eee;color:#333}

    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}

    @media (max-width:880px){.grid{grid-template-columns:1fr}header{padding:14px}}
  </style>
</head>
<body>
  <header>
    <div class="container top">
      <div class="brand">
        <img src="kkk.png" alt="St. Michael's Academy Gandhinagar Logo">
        <div>
          <h1>St. Michael's Academy Gandhinagar</h1>
          <div class="meta">Class: <strong>6D</strong> &nbsp;•&nbsp; Class Teacher: <strong>Pelci Malar Mam</strong> &nbsp;•&nbsp; Academic Year: <strong>2025–2026</strong></div>
        </div>
      </div>
      <div>
        <div style="text-align:right;font-size:13px">Class Portal</div>
      </div>
    </div>
  </header>

  <main class="container">
    <div class="grid">
      <section class="card">
        <div class="ann">
          <h3>Announcements</h3>
          <p id="annText">Welcome to Class 6D! Please check the timetable and latest assignments. Parent–teacher meeting on <strong>November 20, 2025</strong>.</p>
        </div>

        <hr style="margin:12px 0;border:none;border-top:1px solid #f1f1f1">

        <h3 style="margin-bottom:8px">Timetable (Mon–Fri)</h3>
        <div style="overflow:auto">
          <table>
            <thead>
              <tr><th>Period</th><th>Time</th><th>Subject</th></tr>
            </thead>
            <tbody>
              <tr><td>1</td><td>9:00 — 9:40</td><td>Mathematics</td></tr>
              <tr><td>2</td><td>9:40 — 10:20</td><td>English</td></tr>
              <tr><td>3</td><td>10:40 — 11:20</td><td>Science</td></tr>
              <tr><td>4</td><td>11:20 — 12:00</td><td>Social Studies</td></tr>
              <tr><td>5</td><td>12:00 — 12:40</td><td>Second Language</td></tr>
              <tr><td>6</td><td>1:00 — 1:40</td><td>Computer/Art</td></tr>
            </tbody>
          </table>
        </div>

        <hr style="margin:12px 0;border:none;border-top:1px solid #f1f1f1">

        <h3>Assignments</h3>
        <ul id="assignList">
          <li>CARNIVAL-15-11-2025</li>
          <li>Science exhibition -29-11-2025</li>
        </ul>

        <hr style="margin:12px 0;border:none;border-top:1px solid #f1f1f1">

        <h3>Quick tools</h3>
        <div style="display:flex;gap:8px;flex-wrap:wrap">
          <button onclick="window.print()">Print Page</button>
          <button class="secondary" onclick="downloadCSV()">Download Student List</button>
        </div>
      </section>

      <aside>
        <div class="card" style="margin-bottom:14px">
          <h3 style="margin-bottom:8px">Students — 6D</h3>
          <div class="students" id="students">
            <div class="student"><div class="avatar">NK</div><div><strong>navarjun</strong><div style="font-size:13px;color:var(--muted)">Roll: 1</div></div></div>
            <div class="student"><div class="avatar">TS</div><div><strong>trisha</strong><div style="font-size:13px;color:var(--muted)">Roll: 2</div></div></div>
            <div class="student"><div class="avatar">NL</div><div><strong>nalan</strong><div style="font-size:13px;color:var(--muted)">Roll: 3</div></div></div>
             <div class="student"><div class="avatar">VN</div><div><strong>varun</strong><div style="font-size:13px;color:var(--muted)">Roll:4</div></div></div>
            <div class="student"><div class="avatar">MH</div><div><strong>mahith</strong><div style="font-size:13px;color:var(--muted)">Roll: 5</div></div></div>
            <div class="student"><div class="avatar">MK</div><div><strong>mokesh</strong><div style="font-size:13px;color:var(--muted)">Roll: 6</div></div></div>
          </div>

          <form id="addStudentForm" style="margin-top:10px" onsubmit="addStudent(event)">
            <label for="sname">Student name</label>
            <input type="text" id="sname" placeholder="Full name" required>
            <label for="sroll">Roll number</label>
            <input type="text" id="sroll" placeholder="e.g. 7" required>
            <button type="submit">Add Student</button>
          </form>
        </div>

        <div class="card">
          <h3>Contact</h3>
          <p style="margin:6px 0">Class Teacher: <strong>Pelci Malar Mam</strong></p>
          <p style="margin:6px 0">Email: <a href="mailto:pelci.malar@stmichaels.edu">pelci.malar@stmichaels.edu</a></p>
          <p style="margin:6px 0">Phone: <a href="tel:+911234567890">+91 12345 67890</a></p>
        </div>
      </aside>
    </div>

    <footer class="card" style="margin-top:20px">
      <small>Designed for Class 6D • St. Michael's Academy Gandhinagar — © 2025</small>
    </footer>
  </main>

  <script>
    function el(q){return document.querySelector(q)}
    function addStudent(e){
      e.preventDefault();
      const name = el('#sname').value.trim();
      const roll = el('#sroll').value.trim();
      if(!name||!roll) return;
      const container = el('#students');
      const initials = name.split(' ').map(s=>s[0]||'').slice(0,2).join('').toUpperCase();
      const div = document.createElement('div');
      div.className='student';
      div.innerHTML = `<div class="avatar">${initials}</div><div><strong>${escapeHtml(name)}</strong><div style="font-size:13px;color:var(--muted)">Roll: ${escapeHtml(roll)}</div></div>`;
      container.appendChild(div);
      el('#addStudentForm').reset();
    }
    function escapeHtml(s){return s.replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;')}

    function downloadCSV(){
      const rows=[];
      document.querySelectorAll('#students .student').forEach((st,idx)=>{
        const name = st.querySelector('strong').innerText;
        const roll = st.querySelector('div[style]').innerText.replace('Roll: ','');
        rows.push([idx+1, name, roll]);
      });
      let csv = 'No,Name,Roll\n' + rows.map(r=>r.map(c=>`"${c}"`).join(',')).join('\n');
      const blob = new Blob([csv], {type: 'text/csv'});
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a'); a.href = url; a.download = 'class-6D-students.csv'; a.click(); URL.revokeObjectURL(url);
    }
  </script>
</body>
</html>
