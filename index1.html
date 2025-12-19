<!DOCTYPE html>
<html>
  <head>
    <base target="_top">
    <meta charset="utf-8" />
    <title>IAC Profile Form</title>
    <style>
      :root {
        --primary-gradient-start: #ea7317;
        --primary-gradient-end: #ea7317;
        --primary-color: #3da5d9;
        --text-dark: #333;
        --text-medium: #666;
        --white: #fff;
        --border-color: #5a6271;
      }
      *{box-sizing:border-box;margin:0;padding:0}
      body{font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;background:linear-gradient(135deg,var(--primary-gradient-start) 0%,var(--primary-gradient-end) 100%);padding:20px;min-height:100vh}
      .container{max-width:700px;margin:0 auto;background:var(--white);padding:28px;border-radius:12px;box-shadow:0 10px 40px rgba(0,0,0,0.12)}
      .header{display:flex;align-items:center;gap:18px;padding-bottom:12px;border-bottom:2px solid var(--border-color);margin-bottom:16px}
      .header-logo{width:90px;border-radius:8px;display:block}
      h2{margin:0;color:var(--text-dark);font-size:22px}
      .subtitle{color:var(--text-medium);margin-top:6px}
      .small{font-size:13px;color:var(--text-medium);margin-bottom:12px}
      .control-row{display:flex;gap:12px;align-items:center;margin-bottom:12px}
      label{display:block;margin-bottom:8px;font-weight:600}
      input,select,textarea{width:100%;padding:12px;border-radius:8px;border:2px solid #e0e0e0;background:#fafafa}
      .btn{padding:10px 16px;border-radius:8px;border:none;cursor:pointer}
      .btn.primary{background:linear-gradient(135deg,var(--primary-gradient-start),var(--primary-gradient-end));color:var(--white)}
      .btn.ghost{background:#fff;border:2px solid var(--primary-color);color:var(--primary-color)}
      .hidden{display:none!important}
      .field{margin-bottom:18px}
      .radio-group{display:flex;gap:12px;align-items:center}
      .radio-label{display:flex;align-items:center;gap:8px;cursor:pointer}
      .radio-label input[type="radio"]{margin:0}
      .message{padding:12px;border-radius:8px;margin-bottom:12px}
      .spinner{display:inline-block;width:16px;height:16px;border:3px solid rgba(255,255,255,0.3);border-radius:50%;border-top-color:white;animation:spin 1s linear infinite;margin-right:8px;vertical-align:middle}
      @keyframes spin{to{transform:rotate(360deg)}}
      a.small-link{color:var(--primary-color);text-decoration:none}
      .phone-row{display:flex;gap:8px;align-items:center}
      .phone-row select{width:40%;max-width:180px}
      .phone-row input{flex:1}
      .program-cta { display:inline-block; margin:8px 8px 8px 0; padding:10px 14px; border-radius:8px; background:#ea7317; color:#fff; text-decoration:none; font-weight:600; }
      .success-box { padding:16px; border-radius:8px; background:#e6ffea; }
      .error-flash { color: #b71c1c; margin-top:8px; font-size:13px; }

      /* Multi-checkbox UI (checkboxes hidden visually; text remains) */
      .multi-checkbox-wrap { border:1px solid #eee; padding:8px; border-radius:8px; max-height:220px; overflow:auto; background:#fff; margin-top:8px; }
      .multi-checkbox-item {
        display:flex;
        align-items:center;
        gap:8px;
        padding:8px 6px;
        border-bottom:1px solid #f1f1f1;
        justify-content: flex-start;
        cursor: pointer;
        transition: background .12s ease;
      }
      /* Hidden native checkbox: kept for form logic but not visible */
      .multi-checkbox-item input[type="checkbox"] {
        position: absolute !important;
        left: -9999px !important;
        width: 1px !important;
        height: 1px !important;
        overflow: hidden !important;
        clip: rect(0 0 0 0) !important;
        white-space: nowrap !important;
      }
      /* label/text area (clickable) */
      .multi-checkbox-item .mk-label {
        flex: 1 1 auto;
        text-align: left;
        white-space: normal;
        margin: 0;
      }
      /* visual selected state */
      .multi-checkbox-item.selected {
        background: #eef7ff;
        border-left: 3px solid #3da5d9;
      }

      .multi-search { width:100%; padding:8px; margin-bottom:8px; border-radius:6px; border:1px solid #ddd; }
      .hint { font-size:12px; color:#666; margin-top:6px; }
      .required-note { color:#b71c1c; font-size:12px; margin-top:6px; }
    </style>
  </head>
  <body>
    <div class="container">
      <header class="header" role="banner">
        <img id="companyLogo" class="header-logo" src="" alt="Company logo" style="display:none" />
        <div>
          <h2>IAC Profile Form</h2>
        </div>
      </header>

      <div class="control-row">
        <label for="personaSelect" style="min-width:120px;">Which describes you the best?</label>
        <select id="personaSelect" aria-label="Select persona" required>
          <option value="">Select Persona</option>
        </select>
      </div>

      <div id="actionButtons" class="control-row hidden">
        <button id="btnNew" class="btn primary">Submit new application</button>
        <button id="btnEdit" class="btn ghost">Edit my submitted application</button>
      </div>

      <div id="workflowArea">
        <div id="facultyCtaArea" class="hidden" style="margin:12px 0;"></div>

        <!-- Description (kept after faculty CTA per your previous request) -->
        <p id="globalDescription" class="small" style="margin-top:8px;">
          Filling this profile form helps us understand your skills, goals, and interests so we can connect you to the right industry training, mentorship, internships, jobs, and career-building opportunities. Your details enable Cloud Counselage and IAC to personalize your journey and match you with programs, guidance, and resources that support your professional growth and future success.
        </p>

        <div id="editEmailArea" class="hidden" style="margin-top:12px;">
          <div class="field" style="display:flex;gap:8px;align-items:center;">
            <input id="editEmailInput" type="email" placeholder="Enter your Email ID (used during submission)" required />
            <button id="loadButton" class="btn primary">Load</button>
          </div>
          <div id="editMsg" class="small">Enter the email you used previously and click on "Load" twice for loading the details to make the necessary changes.</div>
        </div>

        <div id="formContainer" class="hidden" style="margin-top:16px;"></div>

        <div id="messageArea" style="margin-top:12px"></div>
      </div>
    </div>

    <script>
      let PERSONA_FIELDS = {};
      let APP_CONFIG = {};
      let currentPersona = '';
      let currentMode = ''; // 'new'|'edit'
      let isLoadingRecord = false;

      // Fields treated as Yes/No radios
      const YES_NO_FIELDS = [
        "Have you upskilled or taken courses during the break?",
        "Are You Interested in Internship / Job Opportunities?",
        "Are You Considering Transitioning to a Different Domain or Industry?",
        "Are You Open to Part-time, Freelance, or Remote Work Opportunities?",
        "Are You interested in Entrepreneurship as a career option?",
        "Willing to Work Without Stipend for First 3 Months (Full-time Internship)",
        "Would You Like to Connect with Mentors or Industry Professionals?",
        "Would You Like Guidance on Resume Building & Interview Preparation?",
        "Do You Agree to Terms of Engagement?",
        "Do You Agree to Receive Communications from Us?",
        "Do You Want to Become a Community Ambassador?",
        "Internships Completed"
      ];

      // Which fields should be multi-select (we'll render rows of text with hidden checkboxes)
      const MULTI_SELECT_MAP = {
        'Student': [
          "Preferred Industry / Career Path / Field of Interest",
          "Academic Work & Hands-On Experience",
          "Current Skills (Technical & Soft)",
          "Skills You Want to Develop (Next 6–12 Months)"
        ],
        'Working Professional': [
          "Preferred Industry / Career Path / Field of Interest",
          "Current Skills (Technical & Soft)",
          "Skills You Want to Develop (Next 6–12 Months)"
        ],
        'Professional on a Career Break': [
          "Preferred Industry / Career Path / Field of Interest",
          "Current Skills (Technical & Soft)",
          "Skills You Want to Develop (Next 6–12 Months)"
        ]
      };

      // Preferred Internship options
      const INTERNSHIP_DURATION_OPTIONS = ['3 months', '6 months', '6 months+'];

      const personaSelect = document.getElementById('personaSelect');
      const actionButtons = document.getElementById('actionButtons');
      const btnNew = document.getElementById('btnNew');
      const btnEdit = document.getElementById('btnEdit');
      const editEmailArea = document.getElementById('editEmailArea');
      const editEmailInput = document.getElementById('editEmailInput');
      const loadButton = document.getElementById('loadButton');
      const formContainer = document.getElementById('formContainer');
      const messageArea = document.getElementById('messageArea');
      const facultyCtaArea = document.getElementById('facultyCtaArea');
      const companyLogoImg = document.getElementById('companyLogo');
      const globalDescription = document.getElementById('globalDescription');

      function showMessage(text, type='success') {
        messageArea.innerHTML = '<div class="message" style="background:' + (type==='error' ? '#ffe6e6' : '#e6ffea') + ';">' + text + '</div>';
        window.scrollTo({ top: 0, behavior: 'smooth' });
      }
      function clearMessage(){ messageArea.innerHTML = ''; }
      function sanitizeId(s) { return String(s).replace(/[^a-z0-9\-_]/ig,'_'); }

      function createDatalist(id, items) {
        let d = document.getElementById(id);
        if (!d) {
          d = document.createElement('datalist');
          d.id = id;
          document.body.appendChild(d);
        } else { d.innerHTML = ''; }
        (items || []).forEach(it => { const o=document.createElement('option'); o.value=it; d.appendChild(o); });
      }

      // --- DOB YEAR validator: prevents >4-digit years and enforces a sensible range ---
      function validateDOBYear(input) {
        if (!input) return;
        const val = input.value;
        if (!val) { input.setCustomValidity(''); return; }

        if (/^\d{4}-\d{2}-\d{2}$/.test(val)) {
          const parts = val.split('-');
          let yearStr = parts[0] || '';
          if (yearStr.length > 4) yearStr = yearStr.slice(0,4);
          const yearNum = parseInt(yearStr, 10);
          const curYear = (new Date()).getFullYear();
          if (isNaN(yearNum) || yearNum < 1000 || yearNum > curYear) {
            input.setCustomValidity('Please enter a valid year between 1000 and ' + curYear + '.');
          } else {
            input.setCustomValidity('');
          }
          const month = parts[1] ? parts[1].padStart(2,'0') : '01';
          const day = parts[2] ? parts[2].padStart(2,'0') : '01';
          const corrected = yearStr + '-' + month + '-' + day;
          if (corrected !== val) input.value = corrected;
          return;
        }

        if (/^\d{2}[\/\-]\d{2}[\/\-]\d{4}$/.test(val)) {
          const parts = val.split(/[\/\-]/);
          const yearNum = parseInt(parts[2], 10);
          const curYear = (new Date()).getFullYear();
          if (isNaN(yearNum) || yearNum < 1000 || yearNum > curYear) {
            input.setCustomValidity('Please enter a valid year between 1000 and ' + curYear + '.');
          } else {
            input.setCustomValidity('');
          }
          return;
        }
        input.setCustomValidity('');
      }

      // Create a searchable list of text rows (keeps hidden checkboxes for data)
      function createCheckboxList(fieldName, options, required) {
        const wrap = document.createElement('div');
        wrap.className = 'field';
        const label = document.createElement('label'); label.textContent = fieldName; wrap.appendChild(label);

        const help = document.createElement('div'); help.className = 'hint'; help.textContent = 'Tap to select multiple options. Use the search box to filter.'; wrap.appendChild(help);

        const search = document.createElement('input');
        search.type = 'text'; search.className = 'multi-search'; search.placeholder = 'Search...';
        search.id = 'search_' + sanitizeId(fieldName);
        wrap.appendChild(search);

        const listWrap = document.createElement('div'); listWrap.className = 'multi-checkbox-wrap'; listWrap.id = 'wrap_' + sanitizeId(fieldName);

        options.forEach((opt, idx) => {
          // container row (clicking toggles selection)
          const row = document.createElement('div');
          row.className = 'multi-checkbox-item';
          row.tabIndex = 0;
          // hidden native checkbox (keeps all existing logic intact)
          const cb = document.createElement('input'); cb.type = 'checkbox'; cb.value = opt; cb.name = fieldName; cb.id = 'chk_' + sanitizeId(fieldName + '_' + idx);
          cb.dataset.group = 'multi';
          // visible text node
          const txt = document.createElement('div'); txt.className = 'mk-label'; txt.textContent = opt;

          // clicking the row toggles the hidden checkbox and visual state
          row.addEventListener('click', function(e){
            // ignore clicks if they target other controls (not expected here)
            cb.checked = !cb.checked;
            row.classList.toggle('selected', cb.checked);
          });
          // allow keyboard toggle (Space/Enter)
          row.addEventListener('keydown', function(e){
            if (e.key === ' ' || e.key === 'Spacebar' || e.key === 'Enter') {
              e.preventDefault();
              cb.checked = !cb.checked;
              row.classList.toggle('selected', cb.checked);
            }
          });

          // if prefilled later the cb.checked will be set and we should reflect that visually.
          // we'll leave that to populateControlsFromPrefill() which sets cb.checked and then we can sync class
          row.appendChild(cb);
          row.appendChild(txt);
          listWrap.appendChild(row);
        });

        wrap.appendChild(listWrap);

        // client-side search filter
        search.addEventListener('input', function(){
          const q = (this.value || '').trim().toLowerCase();
          const items = listWrap.querySelectorAll('.multi-checkbox-item');
          items.forEach(it => {
            const txt = (it.textContent || '').toLowerCase();
            it.style.display = (!q || txt.indexOf(q) !== -1) ? '' : 'none';
          });
        });

        // optional required note: we'll validate group required on submit
        if (required) {
          const rn = document.createElement('div'); rn.className='required-note'; rn.textContent='(Required — select at least one)'; wrap.appendChild(rn);
        }

        return wrap;
      }

      // populate checkbox groups from prefill values (comma-separated)
      function prefillCheckboxGroups(formEl, prefillValues) {
        const keys = Object.keys(prefillValues || {});
        keys.forEach(k => {
          const val = prefillValues[k];
          if (!val) return;
          // find hidden checkboxes with that name
          const chks = Array.from(formEl.querySelectorAll('input[type="checkbox"][name="' + k + '"]'));
          if (!chks || chks.length === 0) return;
          const parts = String(val || '').split(',').map(s=>s.trim()).filter(Boolean);
          chks.forEach(cb => {
            if (parts.indexOf(cb.value) !== -1) {
              cb.checked = true;
              // find row container and mark visual selected
              const row = cb.parentNode;
              if (row && row.classList) row.classList.add('selected');
            } else {
              cb.checked = false;
              const row = cb.parentNode;
              if (row && row.classList) row.classList.remove('selected');
            }
          });
        });
      }

      function populateControlsFromPrefill(formEl, prefillValues) {
        if (!prefillValues) return;
        const inputs = Array.from(formEl.querySelectorAll('input, textarea, select'));
        inputs.forEach(i => {
          const name = i.name; if (!name) return;
          const val = prefillValues[name];
          if (val === undefined || val === null) return;
          if (i.type === 'checkbox') {
            // group checkboxes handled specially below
            if (i.dataset && i.dataset.group === 'multi') {
              // skip here
            } else {
              i.checked = String(val).toLowerCase() === 'yes' || String(val).toLowerCase() === 'true';
            }
          } else if (i.type === 'radio') { if (i.value && String(i.value).toLowerCase() === String(val).toLowerCase()) i.checked = true; }
          else if (i.type === 'file') { /* cannot prefill */ }
          else {
            // If this is the DOB field and stored value is DD/MM/YYYY, convert to yyyy-mm-dd for type=date
            if (i.type === 'date' && /date of birth/i.test(name) && typeof val === 'string' && /^\d{2}[\/\-]\d{2}[\/\-]\d{4}$/.test(val)) {
              const p = val.split(/[\/\-]/);
              const dd = p[0].padStart(2,'0'); const mm = p[1].padStart(2,'0'); const yyyy = p[2];
              i.value = yyyy + '-' + mm + '-' + dd;
            } else {
              i.value = val;
            }
          }
        });
        // now prefill checkbox groups and sync visual state
        prefillCheckboxGroups(formEl, prefillValues);
      }

      function buildFormForPersona(persona, prefillValues) {
        formContainer.innerHTML = ''; formContainer.classList.remove('hidden');
        const fields = PERSONA_FIELDS[persona] || [];
        const formEl = document.createElement('form'); formEl.id='personaForm'; formEl.enctype='multipart/form-data';
        formEl.addEventListener('submit', function(e){ e.preventDefault(); clearMessage(); handleSubmit(persona); });

        // datalists / source lists
        if (APP_CONFIG.selectOptions) {
          createDatalist('sources_list', APP_CONFIG.selectOptions.sources || []);
          createDatalist('skills_list', APP_CONFIG.selectOptions.skills || []);
          createDatalist('countries_list', APP_CONFIG.selectOptions.countries || []);
          createDatalist('universities_list', APP_CONFIG.selectOptions.universities || []);
          createDatalist('companies_list', APP_CONFIG.selectOptions.companies || []);
        }

        // degree datalist from config
        createDatalist('degrees_list', APP_CONFIG.degrees || []);

        // year-of-graduation options (1900..2100)
        const gradYears = APP_CONFIG.years || [];

        // country codes list
        const countryCodes = APP_CONFIG.countryCodes || [];

        fields.forEach(name => {
          if (!name || String(name).trim() === '-- Select --') return;

          // Terms and Conditions handled as before (required)
          if (/^\s*Terms\s*&\s*Conditions\s*$/i.test(name)) {
            const fieldWrap = document.createElement('div'); fieldWrap.className='field';
            const label = document.createElement('label'); label.textContent='Do you agree with our terms & conditions?'; fieldWrap.appendChild(label);
            const radioRow = document.createElement('div'); radioRow.className='radio-group';
            ['Yes','No'].forEach((opt, idx) => {
              const id='field_'+sanitizeId(name+'_'+opt);
              const wrapper=document.createElement('label'); wrapper.className='radio-label';
              const r=document.createElement('input'); r.type='radio'; r.name=name; r.value=opt; r.id=id;
              if (idx===0) r.required = true; // set required on first radio to enforce group required
              wrapper.appendChild(r); wrapper.appendChild(document.createTextNode(opt)); radioRow.appendChild(wrapper);
            });
            fieldWrap.appendChild(radioRow);
            const termsBtn=document.createElement('button'); termsBtn.type='button'; termsBtn.className='btn ghost'; termsBtn.style.marginTop='8px'; termsBtn.textContent='View Terms & Conditions';
            termsBtn.addEventListener('click', ()=> window.open(APP_CONFIG.termsUrl || '#','_blank'));
            fieldWrap.appendChild(termsBtn);
            const linkRow=document.createElement('div'); linkRow.style.marginTop='8px';
            const termsLink=document.createElement('label'); termsLink.href=''; termsLink.target=''; termsLink.rel='noopener noreferrer'; termsLink.className='small-link'; termsLink.textContent=' ';
            linkRow.appendChild(termsLink); fieldWrap.appendChild(linkRow);
            formEl.appendChild(fieldWrap); return;
          }

          // YES/NO fields (including Internships Completed)
          if (YES_NO_FIELDS.includes(name)) {
            const fieldWrap = document.createElement('div'); fieldWrap.className='field';
            const label = document.createElement('label'); label.textContent = name; fieldWrap.appendChild(label);
            const radioRow = document.createElement('div'); radioRow.className='radio-group';
            ['Yes','No'].forEach((opt, idx) => {
              const id='field_'+sanitizeId(name+'_'+opt);
              const wrapper=document.createElement('label'); wrapper.className='radio-label';
              const r=document.createElement('input'); r.type='radio'; r.name=name; r.value=opt; r.id=id;
              if (idx===0) r.required = true; // required on group
              wrapper.appendChild(r); wrapper.appendChild(document.createTextNode(opt)); radioRow.appendChild(wrapper);
            });
            fieldWrap.appendChild(radioRow); formEl.appendChild(fieldWrap); return;
          }

          // Resume / file input (required)
          if (/upload resume/i.test(name) || /resume/i.test(name)) {
            const fieldWrap=document.createElement('div'); fieldWrap.className='field';
            const label=document.createElement('label'); label.textContent = name;
            const input=document.createElement('input'); input.type='file'; input.name=name; input.id='field_'+sanitizeId(name); input.accept='application/pdf'; input.required = true;
            const help=document.createElement('div'); help.className='small'; help.textContent='Only PDF files are accepted (max 10MB)';
            fieldWrap.appendChild(label); fieldWrap.appendChild(input); fieldWrap.appendChild(help); formEl.appendChild(fieldWrap); return;
          }

          // Preferred Industry / multi text-list (for personas that require multi)
          if (/Preferred Industry \/ Career Path \/ Field of Interest/i.test(name)) {
            const shouldMulti = (MULTI_SELECT_MAP[persona] || []).indexOf(name) !== -1;
            if (shouldMulti) {
              const optList = (APP_CONFIG.selectOptions && APP_CONFIG.selectOptions.industries) || [];
              const wrap = createCheckboxList(name, optList, true);
              formEl.appendChild(wrap); return;
            } else {
              const fieldWrap=document.createElement('div'); fieldWrap.className='field';
              const label=document.createElement('label'); label.textContent = name; fieldWrap.appendChild(label);
              const sel=document.createElement('select'); sel.name=name; sel.id='field_'+sanitizeId(name); sel.required = true;
              const ph=document.createElement('option'); ph.value=''; ph.textContent='-- Select Industry --'; sel.appendChild(ph);
              const industries=(APP_CONFIG.selectOptions && APP_CONFIG.selectOptions.industries) || [];
              industries.forEach(it=>{ const o=document.createElement('option'); o.value=it; o.textContent=it; sel.appendChild(o); });
              fieldWrap.appendChild(sel); formEl.appendChild(fieldWrap); return;
            }
          }

          // Preferred Internship Duration dropdown
          if (/Preferred Internship Duration/i.test(name)) {
            const fieldWrap=document.createElement('div'); fieldWrap.className='field';
            const label=document.createElement('label'); label.textContent = name; fieldWrap.appendChild(label);
            const sel = document.createElement('select'); sel.name = name; sel.id = 'field_'+sanitizeId(name); sel.required = true;
            const ph = document.createElement('option'); ph.value=''; ph.textContent='-- Select Duration --'; sel.appendChild(ph);
            INTERNSHIP_DURATION_OPTIONS.forEach(it => { const o=document.createElement('option'); o.value = it; o.textContent = it; sel.appendChild(o); });
            fieldWrap.appendChild(sel); formEl.appendChild(fieldWrap); return;
          }

          // Mobile Number with country code select
          if (/mobile|phone|number/i.test(name) && /mobile/i.test(name)) {
            const fieldWrap=document.createElement('div'); fieldWrap.className='field';
            const label=document.createElement('label'); label.textContent = name; fieldWrap.appendChild(label);
            const phoneRow=document.createElement('div'); phoneRow.className='phone-row';
            const codeSelect=document.createElement('select'); codeSelect.name='Mobile Country Code'; codeSelect.id='field_Mobile_Country_CODE'; codeSelect.required = true;
            const defOpt = document.createElement('option'); defOpt.value=''; defOpt.textContent='Code'; codeSelect.appendChild(defOpt);
            (countryCodes || []).forEach(cc => {
              const o=document.createElement('option'); o.value = cc.code; o.textContent = cc.code + ' ' + cc.country; codeSelect.appendChild(o);
            });
            const phoneInput=document.createElement('input'); phoneInput.type='tel'; phoneInput.name=name; phoneInput.id='field_'+sanitizeId(name); phoneInput.placeholder='Enter phone number'; phoneInput.required = true;
            phoneRow.appendChild(codeSelect); phoneRow.appendChild(phoneInput); fieldWrap.appendChild(phoneRow);
            formEl.appendChild(fieldWrap); return;
          }

          // DEGREE fields -> searchable datalist using APP_CONFIG.degrees
          if (/\bdegree\b/i.test(name)) {
            const fieldWrap=document.createElement('div'); fieldWrap.className='field';
            const label=document.createElement('label'); label.textContent = name; fieldWrap.appendChild(label);
            const input=document.createElement('input'); input.type='text'; input.name=name; input.id='field_'+sanitizeId(name);
            input.setAttribute('list','degrees_list'); input.placeholder = 'Type or select your degree (e.g. B.Tech., M.Tech.)';
            input.required = true;
            fieldWrap.appendChild(input); formEl.appendChild(fieldWrap); return;
          }

          // Year of Study for Student should be a dropdown (1st,2nd,3rd,Final,Postgraduate)
          if (/Year of Study/i.test(name)) {
            const fieldWrap=document.createElement('div'); fieldWrap.className='field';
            const label=document.createElement('label'); label.textContent = name; fieldWrap.appendChild(label);
            const sel = document.createElement('select'); sel.name = name; sel.id = 'field_'+sanitizeId(name); sel.required = true;
            const ph = document.createElement('option'); ph.value=''; ph.textContent='-- Select Year of Study --'; sel.appendChild(ph);
            (["1st Year","2nd Year","3rd Year","Final Year","Postgraduate"]).forEach(it => { const o=document.createElement('option'); o.value = it; o.textContent = it; sel.appendChild(o); });
            fieldWrap.appendChild(sel); formEl.appendChild(fieldWrap); return;
          }

          // Year of Graduation / Expected Graduation for students and Year of Graduation for others -> dropdown 1900..2100
          if (/Year of Graduation\/Expected Graduation|Year of Graduation/i.test(name)) {
            const fieldWrap=document.createElement('div'); fieldWrap.className='field';
            const label=document.createElement('label'); label.textContent = name; fieldWrap.appendChild(label);
            const sel = document.createElement('select'); sel.name = name; sel.id = 'field_'+sanitizeId(name); sel.required = true;
            const ph = document.createElement('option'); ph.value=''; ph.textContent='-- Select Year --'; sel.appendChild(ph);
            (APP_CONFIG.years || []).forEach(y => { const o=document.createElement('option'); o.value = y; o.textContent = y; sel.appendChild(o); });
            fieldWrap.appendChild(sel); formEl.appendChild(fieldWrap); return;
          }

          // Academic Work & Hands-On Experience -> multi-list for students
          if (/Academic Work & Hands-On Experience/i.test(name)) {
            const shouldMulti = (MULTI_SELECT_MAP[persona] || []).indexOf(name) !== -1;
            if (shouldMulti) {
              const optList = (APP_CONFIG.selectOptions && APP_CONFIG.selectOptions.skills) || [];
              const wrap = createCheckboxList(name, optList, true);
              formEl.appendChild(wrap); return;
            }
          }

          // Datalist enabled fields / others with multi handling
          let input;

          // --- INSERTED SNIPPET START ---
          // Industry (Current / Most Recent) -> render same industry dropdown as Preferred Industry
          if (/Industry\s*\(Current\s*\/\s*Most\s*Recent\)/i.test(name)) {
            const fieldWrap = document.createElement('div'); fieldWrap.className='field';
            const label = document.createElement('label'); label.textContent = name; fieldWrap.appendChild(label);

            // Use the industries list from APP_CONFIG.selectOptions (falls back to empty array)
            const sel = document.createElement('select');
            sel.name = name;
            sel.id = 'field_' + sanitizeId(name);
            sel.required = true;

            const ph = document.createElement('option');
            ph.value = '';
            ph.textContent = '-- Select Industry --';
            sel.appendChild(ph);

            const industries = (APP_CONFIG.selectOptions && APP_CONFIG.selectOptions.industries) || [];
            industries.forEach(it => {
              const o = document.createElement('option');
              o.value = it;
              o.textContent = it;
              sel.appendChild(o);
            });

            fieldWrap.appendChild(sel);
            formEl.appendChild(fieldWrap);
            return;
          }
          // --- INSERTED SNIPPET END ---

          if (/How Did You Hear About Us|How Did You Hear/i.test(name)) {
            input = document.createElement('input'); input.type = 'text'; input.setAttribute('list','sources_list'); input.placeholder='Select or type to search...'; input.required = true;
          } else if (/Name of Your College|college|University/i.test(name)) {
            input = document.createElement('input'); input.type = 'text'; input.setAttribute('list','universities_list'); input.placeholder='Type to search your college... (Select "Other" if not listed)'; input.required = true;
          } else if (/Country/i.test(name)) {
            input = document.createElement('input'); input.type = 'text'; input.setAttribute('list','countries_list'); input.placeholder='Type to search country...'; input.required = true;
          } else if (/Current \/ Most Recent Company|Start typing company|company/i.test(name)) {
            input = document.createElement('input'); input.type = 'text'; input.setAttribute('list','companies_list'); input.placeholder='Start typing to see suggestions or enter a new company name'; input.required = true;
          } else if (/Current Skills \(Technical & Soft\)|Skills You Want to Develop \(Next 6–12 Months\)/i.test(name)) {
            const shouldMulti = (MULTI_SELECT_MAP[persona] || []).indexOf(name) !== -1;
            if (shouldMulti) {
              const optList = (APP_CONFIG.selectOptions && APP_CONFIG.selectOptions.skills) || [];
              const wrap = createCheckboxList(name, optList, true);
              formEl.appendChild(wrap); return;
            }
            input = document.createElement('input'); input.type = 'text'; input.setAttribute('list','skills_list'); input.placeholder='Type to search skills... (comma separated for multiple)'; input.required = true;
          } else if (/linkedin|portfolio|github/i.test(name)) {
            input = document.createElement('input'); input.type = 'url'; input.placeholder='https://'; input.required = true;
          } else if (/date of birth|date/i.test(name)) {
            // Use native date picker (calendar) AND allow manual typing.
            // We'll validate year size/range via validateDOBYear(). Server expects DD/MM/YYYY,
            // so submitForm will convert yyyy-mm-dd -> DD/MM/YYYY before sending.
            input = document.createElement('input');
            input.type = 'date';                         // enables calendar popup
            input.name = name;
            input.id = 'field_' + sanitizeId(name);
            input.required = true;
            // Optional: set a reasonable min/max (keeps calendar sensible)
            input.min = '1000-01-01';                    // earliest allowed year 1000
            // set max to today's date so future DOBs aren't chosen
            const today = new Date();
            const yyyy = today.getFullYear();
            const mm = String(today.getMonth() + 1).padStart(2, '0');
            const dd = String(today.getDate()).padStart(2, '0');
            input.max = yyyy + '-' + mm + '-' + dd;
            // validate while typing + on blur
            input.setAttribute('oninput', 'validateDOBYear(this)');
            input.setAttribute('onblur', 'validateDOBYear(this)');
            const hint = document.createElement('div'); hint.className='hint'; hint.textContent = 'You can choose from the calendar or type the date. Year must be between 1000 and current year.';
            const fieldWrap = document.createElement('div'); fieldWrap.className='field';
            const label = document.createElement('label'); label.textContent = name;
            fieldWrap.appendChild(label); fieldWrap.appendChild(input); fieldWrap.appendChild(hint);
            formEl.appendChild(fieldWrap);
            return;
          } else if (/email/i.test(name)) {
            input = document.createElement('input'); input.type = 'email'; input.placeholder = name; input.required = true;
          } else if (/phone|mobile|number/i.test(name)) {
            // fallback phone if not matched as mobile
            input = document.createElement('input'); input.type = 'tel'; input.placeholder='Enter phone number'; input.required = true;
          } else if (name.length > 80 || /provide|details|aspirations|support|expect/i.test(name)) {
            input = document.createElement('textarea'); input.rows = 4; input.required = true;
          } else {
            input = document.createElement('input'); input.type = 'text'; input.placeholder = name; input.required = true;
          }

          input.id = 'field_' + sanitizeId(name);
          input.name = name;
          const fieldWrap = document.createElement('div'); fieldWrap.className='field';
          const label = document.createElement('label'); label.textContent = name;
          fieldWrap.appendChild(label); fieldWrap.appendChild(input); formEl.appendChild(fieldWrap);
        });

        // submit/back buttons
        const row = document.createElement('div'); row.className='control-row';
        const submitBtn = document.createElement('button'); submitBtn.type='submit'; submitBtn.className='btn primary'; submitBtn.textContent='Submit Application';
        const backBtn = document.createElement('button'); backBtn.type='button'; backBtn.className='btn'; backBtn.style.marginLeft='8px'; backBtn.textContent='Back';
        backBtn.addEventListener('click', function(){ resetToPersonaSelection(); });
        row.appendChild(submitBtn); row.appendChild(backBtn); formEl.appendChild(row);

        formContainer.appendChild(formEl);

        if (prefillValues) {
          populateControlsFromPrefill(formEl, prefillValues);
          // show existing resume link if any
          const resumeKey = Object.keys(prefillValues).find(k => /resume/i.test(k));
          if (resumeKey && prefillValues[resumeKey]) {
            const fileUrl = prefillValues[resumeKey];
            const fileNote = document.createElement('div'); fileNote.className='small'; fileNote.style.marginTop='6px';
            const a = document.createElement('a'); a.href=fileUrl; a.target='_blank'; a.rel='noopener noreferrer'; a.textContent='Download existing resume';
            fileNote.appendChild(a);
            const resumeInput = formEl.querySelector('input[type="file"][name="' + resumeKey + '"]');
            if (resumeInput && resumeInput.parentNode) resumeInput.parentNode.appendChild(fileNote);
            else formEl.appendChild(fileNote);
          }
          // After prefilling hidden checkboxes, ensure visual rows reflect checked values
          // (prefillCheckboxGroups already sets row.selected class)
        }
      }

      // show temporary error next to an input
      function showTempError(el, msg) {
        // remove existing
        const existing = el.parentNode.querySelector('.error-flash');
        if (existing) existing.remove();
        const div = document.createElement('div'); div.className='error-flash'; div.textContent = msg;
        el.parentNode.appendChild(div);
        setTimeout(()=>{ if (div && div.parentNode) div.parentNode.removeChild(div); }, 4000);
      }

      // validate that required checkbox groups have at least one checked
      function validateMultiCheckboxRequired(persona) {
        const groups = MULTI_SELECT_MAP[persona] || [];
        for (let i=0;i<groups.length;i++) {
          const name = groups[i];
          // make sure field exists on this persona (some personas may not include all)
          const groupElems = document.querySelectorAll('input[type="checkbox"][name="' + name + '"]');
          if (!groupElems || groupElems.length === 0) continue;
          const anyChecked = Array.from(groupElems).some(cb => cb.checked);
          if (!anyChecked) {
            // scroll into view and show message
            const first = groupElems[0];
            if (first && first.parentNode) first.parentNode.scrollIntoView({behavior:'smooth', block:'center'});
            showMessage('Please select at least one option for: ' + name, 'error');
            return false;
          }
        }
        return true;
      }

      // ---------- submit logic (duplicate email check for new) ----------
      function handleSubmit(persona) {
        const form = document.getElementById('personaForm');
        if (!form) return;
        // client-side constraint validation (HTML5)
        if (!form.checkValidity()) {
          const firstInvalid = form.querySelector(':invalid');
          if (firstInvalid) firstInvalid.focus();
          showMessage('Please complete all required fields and fix any errors highlighted in the form.', 'error');
          return;
        }

        // validate required checkbox groups
        if (!validateMultiCheckboxRequired(persona)) return;

        const emailInput = form.querySelector('input[type="email"], input[name*="Email"]');
        const emailVal = emailInput ? (emailInput.value || '').trim() : '';
        if (currentMode === 'new') {
          if (!emailVal) { showMessage('Please provide an Email ID before submitting.', 'error'); return; }
          const submitBtn = form.querySelector('button[type="submit"]');
          if (submitBtn) { submitBtn.disabled = true; const spinner=document.createElement('span'); spinner.className='spinner'; submitBtn.prepend(spinner); }
          google.script.run.withSuccessHandler(function(exists){
            if (submitBtn) { submitBtn.disabled = false; const sp = submitBtn.querySelector('.spinner'); if (sp && sp.parentNode) sp.parentNode.removeChild(sp); }
            if (exists) { showMessage('This email ID already exists within the records. Kindly enter the new email ID or edit the submitted application', 'error'); return; }
            submitForm(persona);
          }).withFailureHandler(function(err){
            if (submitBtn) { submitBtn.disabled = false; const sp = submitBtn.querySelector('.spinner'); if (sp && sp.parentNode) sp.parentNode.removeChild(sp); }
            showMessage('Server error while checking email: ' + (err && err.message ? err.message : String(err)), 'error');
          }).emailExists(persona, emailVal);
        } else {
          submitForm(persona);
        }
      }

      function submitForm(persona) {
        const form = document.getElementById('personaForm'); if (!form) return;
        // gather values
        const values = {}; const fileReads = [];

        // handle checkbox groups first (unique group names)
        const allGroupCheckboxes = Array.from(form.querySelectorAll('input[type="checkbox"][data-group="multi"]'));
        const groupNames = Array.from(new Set(allGroupCheckboxes.map(cb => cb.name)));
        groupNames.forEach(name => {
          const selected = Array.from(form.querySelectorAll('input[type="checkbox"][name="' + name + '"]:checked')).map(cb => cb.value);
          values[name] = selected.join(', ');
        });

        // now iterate other inputs
        const inputs = Array.from(form.querySelectorAll('input, textarea, select'));
        inputs.forEach(i => {
          // skip checkbox group inputs since already handled
          if (i.type === 'checkbox' && i.dataset && i.dataset.group === 'multi') return;

          if (i.type === 'file') {
            const f = i.files && i.files[0];
            if (f) {
              // client-side validations BEFORE reading the file
              if (f.type !== 'application/pdf') { showMessage('Please upload only PDF files for resume.', 'error'); throw new Error('Invalid file type'); }
              const MAX_BYTES = 10 * 1024 * 1024;
              if (f.size > MAX_BYTES) { showMessage('Resume exceeds maximum allowed size of 10 MB. Please upload a smaller file.', 'error'); throw new Error('File too large'); }

              const p = new Promise((resolve,reject)=>{ const reader = new FileReader(); reader.onload = function(e){ values[i.name] = { filename: f.name, mimeType: f.type, base64: e.target.result.split(',')[1] }; resolve(); }; reader.onerror = function(err){ reject(err); }; reader.readAsDataURL(f); });
              fileReads.push(p);
            } else values[i.name] = values[i.name] || '';
          } else if (i.type === 'checkbox') {
            // single checkbox boolean (if any)
            if (!(i.dataset && i.dataset.group === 'multi')) {
              values[i.name] = i.checked ? (i.value || 'Yes') : 'No';
            }
          } else if (i.type === 'radio') { if (i.checked) values[i.name] = i.value; }
          else if (i.tagName.toLowerCase() === 'select' && i.multiple) {
            // legacy: if any multiple selects left, handle them
            const selected = Array.from(i.options).filter(o => o.selected).map(o => o.value);
            values[i.name] = selected.join(', ');
          } else {
            values[i.name] = i.value || '';
          }
        });

        // --- convert any type="date" value (yyyy-mm-dd) into DD/MM/YYYY for server ---
        const dobKey = Object.keys(values).find(k => /date of birth/i.test(k));
        if (dobKey && values[dobKey]) {
          const v = String(values[dobKey]).trim();
          if (/^\d{4}-\d{2}-\d{2}$/.test(v)) {
            const parts = v.split('-'); // [yyyy, mm, dd]
            values[dobKey] = parts[2] + '/' + parts[1] + '/' + parts[0];
          }
          // if user typed DD/MM/YYYY already (unlikely for type=date), keep as-is
        }

        // minimal validation
        const emailFieldName = Object.keys(values).find(h => /email/i.test(h));
        if (!emailFieldName || !values[emailFieldName].trim()) { showMessage('Please provide a valid Email ID in the form before submitting.', 'error'); return; }

        // T&C must be Yes
        const tAndCKey = Object.keys(values).find(k => /^\s*Terms\s*&\s*Conditions\s*$/i.test(k));
        if (tAndCKey && String(values[tAndCKey] || '').toLowerCase() !== 'yes') { showMessage('You must agree to the terms & conditions to proceed.', 'error'); return; }

        // Validate DOB client-side format too (DD/MM/YYYY)
        if (dobKey) {
          const dobVal = String(values[dobKey] || '');
          if (!/^\d{2}[\/\-]\d{2}[\/\-]\d{4}$/.test(dobVal)) { showMessage('Date of Birth must be in DD/MM/YYYY format.', 'error'); return; }
          const parts = dobVal.split(/[\/\-]/);
          const yyyy = parseInt(parts[2],10);
          const curYear = (new Date()).getFullYear();
          if (isNaN(yyyy) || yyyy < 1000 || yyyy > curYear) { showMessage('Date of Birth year must be between 1000 and ' + curYear + '.', 'error'); return; }
        }

        Promise.all(fileReads).then(function(){
          google.script.run.withSuccessHandler(function(resp) {
            if (resp && resp.success) {
              const pu = APP_CONFIG.programUrls || {};
              const gpiUrl = pu.gpi || '#';
              const industryUrl = pu.industryTraining || '#';
              const selUrl = pu.sel || '#';
              const jobsUrl = pu.jobs || '#';

              let html = '<div class="success-box">';
              html += '<strong>' + (resp.message || 'Submitted successfully.') + '</strong><br/><br/>';
              html += '<div>In case you want to access our programs, kindly use the buttons below:</div>';
              html += '<div style="margin-top:12px;">';
              html += '<a class="program-cta" href="' + gpiUrl + '" target="_blank" rel="noopener noreferrer">GPI</a>';
              html += '<a class="program-cta" href="' + industryUrl + '" target="_blank" rel="noopener noreferrer">Industry Training</a>';
              html += '<a class="program-cta" href="' + selUrl + '" target="_blank" rel="noopener noreferrer">Startup Entrepreneurship Launchpad (SEL)</a>';
              html += '<a class="program-cta" href="' + jobsUrl + '" target="_blank" rel="noopener noreferrer">Jobs</a>';
              html += '</div></div>';

              messageArea.innerHTML = html;
              window.scrollTo({ top: 0, behavior: 'smooth' });

              formContainer.classList.add('hidden');
              editEmailArea.classList.add('hidden');
            } else {
              showMessage((resp && resp.message) || 'Something went wrong.', 'error');
            }
          }).withFailureHandler(function(err){
            showMessage('Server error: ' + (err && err.message ? err.message : String(err)), 'error');
          }).upsertRecord({ persona: persona, values: values });
        }).catch(function(err){
          showMessage('File read error: ' + (err && err.message ? err.message : String(err)), 'error');
        });
      }

      // ---------- load for edit (stable) ----------
      function loadRecordForEdit(persona, email) {
        email = (email || '').trim();
        if (!email) { showMessage('Please enter an email to load your submitted details.', 'error'); return; }
        if (isLoadingRecord) return;
        clearMessage(); isLoadingRecord = true;
        if (loadButton) { loadButton.disabled = true; } if (editEmailInput) { editEmailInput.disabled = true; }
        const spinner = document.createElement('span'); spinner.className='spinner'; if (loadButton && loadButton.firstChild) loadButton.insertBefore(spinner, loadButton.firstChild);

        google.script.run.withSuccessHandler(function(resp){
          isLoadingRecord = false; if (loadButton) loadButton.disabled = false; if (editEmailInput) editEmailInput.disabled = false;
          if (spinner && spinner.parentNode) spinner.parentNode.removeChild(spinner);
          if (!resp || !resp.found) {
            showMessage((resp && resp.message) || 'No records found! If you had submitted your details please contact member@industryacademiacommunity.com', 'error');
            formContainer.classList.add('hidden'); return;
          }
          currentMode = 'edit'; buildFormForPersona(persona, resp.values); showMessage('Record loaded. You can modify and submit.');
        }).withFailureHandler(function(err){
          isLoadingRecord = false; if (loadButton) loadButton.disabled = false; if (editEmailInput) editEmailInput.disabled = false;
          if (spinner && spinner.parentNode) spinner.parentNode.removeChild(spinner);
          showMessage('Server error: ' + (err && err.message ? err.message : String(err)), 'error');
        }).fetchRecordForEdit(persona, email);
      }

      function resetToPersonaSelection(){ currentMode=''; editEmailArea.classList.add('hidden'); formContainer.classList.add('hidden'); clearMessage(); }
      function fullReset(){ currentPersona=''; personaSelect.value=''; actionButtons.classList.add('hidden'); resetToPersonaSelection(); }

      personaSelect.addEventListener('change', function(){
        const val = personaSelect.value; clearMessage(); formContainer.classList.add('hidden'); editEmailArea.classList.add('hidden'); facultyCtaArea.classList.add('hidden');
        globalDescription.style.display = '';
        if (!val) { actionButtons.classList.add('hidden'); currentPersona=''; currentMode=''; return; }
        currentPersona = val;
        if (val === 'College Faculty') {
          actionButtons.classList.add('hidden');
          facultyCtaArea.classList.remove('hidden'); facultyCtaArea.innerHTML='';
          const welcome = document.createElement('div'); welcome.innerHTML = '<strong>👨‍🏫 Welcome, College Faculty!</strong><br/>We have a dedicated application form for college faculties.<br/>Click the button below to access the form.'; facultyCtaArea.appendChild(welcome);
          const btn = document.createElement('button'); btn.type='button'; btn.className='btn primary'; btn.style.marginTop='10px'; btn.textContent='Get the Form';
          btn.addEventListener('click', function(){ window.open(APP_CONFIG.collegeFacultyFormUrl || '#','_blank'); });
          facultyCtaArea.appendChild(btn);
          return;
        }
        actionButtons.classList.remove('hidden'); currentMode='';
      });

      btnNew.addEventListener('click', function(){
        if (!currentPersona) { showMessage('Please select a persona first.', 'error'); return; }
        if (currentPersona === 'College Faculty') { window.open(APP_CONFIG.collegeFacultyFormUrl || '#','_blank'); return; }
        currentMode = 'new'; editEmailArea.classList.add('hidden'); buildFormForPersona(currentPersona, {}); clearMessage();
      });

      btnEdit.addEventListener('click', function(){
        if (!currentPersona) { showMessage('Please select a persona first.', 'error'); return; }
        if (currentPersona === 'College Faculty') { window.open(APP_CONFIG.collegeFacultyFormUrl || '#','_blank'); return; }
        currentMode = 'edit'; editEmailArea.classList.remove('hidden'); formContainer.classList.add('hidden'); clearMessage();
      });

      loadButton.addEventListener('click', function(){ const email = editEmailInput.value || ''; if (!currentPersona) { showMessage('Please select persona first.', 'error'); return; } loadRecordForEdit(currentPersona, email); });

      // init
      function init() {
        google.script.run.withSuccessHandler(function(map){
          PERSONA_FIELDS = map || {};
          const keys = Object.keys(PERSONA_FIELDS);
          keys.forEach(k => { const opt=document.createElement('option'); opt.value=k; opt.textContent=k; personaSelect.appendChild(opt); });
          personaSelect.value='';
        }).withFailureHandler(function(err){ showMessage('Failed to load persona options: ' + (err && err.message ? err.message : String(err)), 'error'); }).getPersonaFields();

        google.script.run.withSuccessHandler(function(cfg){
          APP_CONFIG = cfg || {};
          if (APP_CONFIG.logoUrl) { companyLogoImg.src = APP_CONFIG.logoUrl; companyLogoImg.style.display=''; } else companyLogoImg.style.display='none';
        }).withFailureHandler(function(err){ /* silent fallback */ }).getAppConfig();
      }
      document.addEventListener('DOMContentLoaded', init);
    </script>
  </body>
</html>