<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#f6f8f4">
  <title>Resident Directory | Barangay West Visoria</title>
  <style>
    :root {
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color: #1d3028;
      background: #f6f8f4;
      --green: #277353;
      --green-dark: #1b5c41;
      --line: #e8ede8;
      --muted: #78857d;
    }
    * { box-sizing: border-box; }
    body { margin: 0; min-height: 100vh; }
    button, input, select { font: inherit; }
    button, select { cursor: pointer; }
    .sidebar { position: fixed; inset: 0 auto 0 0; z-index: 2; display: flex; width: 248px; flex-direction: column; padding: 25px 17px 18px; border-right: 1px solid var(--line); background: #fff; }
    .brand { display: flex; align-items: center; gap: 13px; padding: 0 8px 28px; }
    .brand-mark { display: grid; width: 46px; height: 46px; place-items: center; border-radius: 14px; background: #eaf4ee; color: var(--green); font-size: 23px; }
    .brand-name { font-size: 13px; font-weight: 750; }
    .brand-sub { margin-top: 3px; color: var(--muted); font-size: 9px; letter-spacing: .1em; text-transform: uppercase; }
    .nav-label { padding: 10px 12px; color: #a0aaa2; font-size: 10px; font-weight: 750; letter-spacing: .14em; text-transform: uppercase; }
    .nav-item { display: flex; align-items: center; gap: 12px; margin: 2px 0; padding: 11px 12px; border-radius: 8px; color: #758179; font-size: 13px; font-weight: 650; text-decoration: none; }
    .nav-item:hover, .nav-item.active { background: #eaf4ee; color: var(--green-dark); }
    .nav-icon { width: 19px; text-align: center; font-size: 16px; }
    .sidebar-footer { margin-top: auto; padding: 15px 9px 0; border-top: 1px solid var(--line); color: var(--muted); font-size: 11px; line-height: 1.6; }
    .main { margin-left: 248px; padding: 0 36px 40px; }
    .topbar { display: flex; min-height: 83px; align-items: center; justify-content: space-between; border-bottom: 1px solid var(--line); color: var(--muted); font-size: 12px; }
    .topbar strong { color: #42544a; font-weight: 650; }
    .content { max-width: 1240px; margin: 0 auto; }
    .page-heading { display: flex; align-items: flex-end; justify-content: space-between; gap: 18px; margin: 30px 0 23px; }
    .page-heading h1 { margin: 0 0 6px; font-size: 27px; letter-spacing: -.045em; }
    .page-heading p { margin: 0; color: var(--muted); font-size: 13px; }
    .panel { overflow: hidden; border: 1px solid var(--line); border-radius: 10px; background: #fff; }
    .panel-head { display: flex; align-items: center; justify-content: space-between; gap: 14px; padding: 18px 19px; border-bottom: 1px solid var(--line); }
    .panel-title { font-size: 14px; font-weight: 750; }
    .panel-subtitle { margin-top: 4px; color: #8b968f; font-size: 11px; }
    .tools { display: grid; grid-template-columns: minmax(210px, 1fr) repeat(3, minmax(125px, auto)); gap: 9px; align-items: center; }
    .search { position: relative; }
    .search-icon { position: absolute; top: 8px; left: 11px; color: #9ba69e; font-size: 14px; pointer-events: none; }
    .search input, .filter-select { width: 100%; height: 36px; border: 1px solid #e1e7e1; border-radius: 7px; outline: 0; background: #fff; color: #58665d; font-size: 11px; }
    .search input { padding: 0 10px 0 32px; }
    .filter-select { padding: 0 9px; }
    .search input:focus, .filter-select:focus { border-color: #76a88e; box-shadow: 0 0 0 3px rgba(39,115,83,.1); }
    .table-wrap { overflow-x: auto; }
    table { width: 100%; border-collapse: collapse; text-align: left; white-space: nowrap; }
    th { padding: 12px 15px; background: #fbfcfa; color: #87928a; font-size: 9px; font-weight: 750; letter-spacing: .08em; text-transform: uppercase; }
    td { padding: 13px 15px; border-top: 1px solid #eff2ef; color: #59675e; font-size: 11px; }
    tbody tr:hover { background: #fbfcfa; }
    .resident-name { color: #2b3b32; font-size: 11px; font-weight: 700; }
    .resident-id, .resident-detail { margin-top: 4px; color: #929d95; font-size: 9px; }
    .status { display: inline-flex; align-items: center; padding: 5px 9px; border-radius: 20px; font-size: 9px; font-weight: 700; }
    .status.active { background: #e8f4ec; color: #327454; }
    .status.moved { background: #fbf2df; color: #8b6a2a; }
    .status.deceased { background: #faeaea; color: #9a5a5a; }
    .empty { padding: 44px 20px; color: #89958c; text-align: center; font-size: 12px; }
    .notice { display: none; margin: 16px 19px 0; padding: 12px 14px; border: 1px solid #f0d4d4; border-radius: 7px; background: #fff5f5; color: #8e4141; font-size: 12px; line-height: 1.5; }
    .notice.visible { display: block; }
    .table-footer { display: flex; align-items: center; justify-content: space-between; gap: 14px; padding: 12px 16px; border-top: 1px solid var(--line); color: #89958c; font-size: 10px; }
    .table-navigation { display: flex; align-items: center; gap: 8px; }
    .page-btn { padding: 7px 10px; border: 1px solid #dfe6df; border-radius: 6px; background: #fff; color: #526158; font-size: 10px; }
    .page-btn:hover:not(:disabled) { border-color: #91b69e; color: var(--green-dark); }
    .page-btn:disabled { cursor: not-allowed; opacity: .45; }
    .page-size { height: 29px; padding: 0 6px; border: 1px solid #dfe6df; border-radius: 6px; background: #fff; color: #526158; font-size: 10px; }
    @media (max-width: 1050px) {
      .main { padding-right: 22px; padding-left: 22px; }
      .panel-head { align-items: flex-start; flex-direction: column; }
      .tools { width: 100%; grid-template-columns: minmax(180px, 1fr) repeat(3, minmax(110px, auto)); }
    }
    @media (max-width: 700px) {
      .sidebar { inset: auto 0 0; width: 100%; height: 62px; flex-direction: row; align-items: center; justify-content: center; padding: 6px 9px; border-top: 1px solid var(--line); border-right: 0; }
      .brand, .nav-label, .sidebar-footer { display: none; }
      .sidebar nav { display: flex; width: 100%; justify-content: space-around; }
      .nav-item { margin: 0; padding: 10px 15px; }
      .main { margin-left: 0; padding: 0 16px 82px; }
      .topbar { min-height: 61px; }
      .page-heading { margin: 23px 0 18px; }
      .page-heading h1 { font-size: 23px; }
      .tools { grid-template-columns: repeat(2, minmax(0, 1fr)); }
      .search { grid-column: 1 / -1; }
      .table-footer { align-items: flex-start; flex-direction: column; }
      .table-navigation { flex-wrap: wrap; }
    }
  </style>
</head>
<body>
  <aside class="sidebar">
    <div class="brand">
      <div class="brand-mark" aria-hidden="true">⌂</div>
      <div><div class="brand-name">Barangay West Visoria</div><div class="brand-sub">Resident Services</div></div>
    </div>
    <div class="nav-label">Workspace</div>
    <nav aria-label="Main navigation">
      <a class="nav-item" href="janalbert.html"><span class="nav-icon" aria-hidden="true">▦</span><span>Overview</span></a>
      <a class="nav-item active" href="#resident-list" aria-current="page"><span class="nav-icon" aria-hidden="true">♙</span><span>Residents</span></a>
    </nav>
    <div class="sidebar-footer">West Visoria Resident Registry</div>
  </aside>
  <main class="main">
    <header class="topbar">
      <div class="crumb">Workspace &nbsp; / &nbsp; <strong>Residents</strong></div>
      <div id="todayLabel" class="top-date"></div>
    </header>
    <div class="content">
      <section class="page-heading">
        <div><h1>Resident directory</h1><p>Search, filter, and browse resident records.</p></div>
      </section>
      <section id="resident-list" class="panel" aria-labelledby="residentTitle">
        <div class="panel-head">
          <div><div id="residentTitle" class="panel-title">Resident records</div><div class="panel-subtitle">Search by name, ID, contact, address, or household</div></div>
          <div class="tools">
            <label class="search">
              <span class="search-icon" aria-hidden="true">⌕</span>
              <input id="searchInput" type="search" placeholder="Search residents..." aria-label="Search residents">
            </label>
            <select id="statusFilter" class="filter-select" aria-label="Filter by status">
              <option value="">All statuses</option><option value="Active">Active</option><option value="Moved">Moved</option><option value="Deceased">Deceased</option>
            </select>
            <select id="purokFilter" class="filter-select" aria-label="Filter by purok"><option value="">All puroks</option></select>
            <select id="voterFilter" class="filter-select" aria-label="Filter by voter registration">
              <option value="">All voter records</option><option value="Yes">Registered voters</option><option value="No">Not registered</option>
            </select>
          </div>
        </div>
        <div id="storageNotice" class="notice" role="alert"></div>
        <div class="table-wrap">
          <table>
            <thead><tr><th>Resident</th><th>Contact</th><th>Address</th><th>Household</th><th>Voter</th><th>Status</th></tr></thead>
            <tbody id="residentRows"></tbody>
          </table>
          <div id="emptyState" class="empty" hidden>No resident records found. Use the Overview page to add residents or load sample data.</div>
        </div>
        <div class="table-footer">
          <span id="recordCount" aria-live="polite">Showing 0 residents</span>
          <div class="table-navigation" aria-label="Resident list pagination">
            <button id="previousPage" class="page-btn" type="button" aria-label="Previous page">Previous</button>
            <span id="pageIndicator" aria-live="polite">Page 1 of 1</span>
            <button id="nextPage" class="page-btn" type="button" aria-label="Next page">Next</button>
            <select id="pageSize" class="page-size" aria-label="Residents per page">
              <option value="10">10 / page</option><option value="25">25 / page</option><option value="50">50 / page</option>
            </select>
          </div>
          <span>West Visoria Resident Registry</span>
        </div>
      </section>
    </div>
  </main>
  <script>
    (() => {
      "use strict";
      const STORAGE_KEY = "westVisoriaResidents";
      const $ = (id) => document.getElementById(id);
      let residents = [];
      let currentPage = 1;
      let pageSize = Number($("pageSize").value);

      function escapeHtml(value) {
        return String(value ?? "").replace(/[&<>"']/g, (character) => ({
          "&": "&amp;", "<": "&lt;", ">": "&gt;", '"': "&quot;", "'": "&#39;"
        })[character]);
      }

      function getPurok(address) {
        const match = String(address || "").match(/purok\s+\d+/i);
        return match ? match[0].replace(/\s+/g, " ") : "";
      }

      function loadResidents() {
        try {
          const stored = localStorage.getItem(STORAGE_KEY);
          if (!stored) return [];
          const parsed = JSON.parse(stored);
          if (!Array.isArray(parsed)) throw new TypeError("Resident storage must contain a list.");
          return parsed;
        } catch (error) {
          console.error("Unable to load resident records.", error);
          $("storageNotice").textContent = "Resident records could not be loaded from this browser. Check browser storage permissions, then reload this page.";
          $("storageNotice").classList.add("visible");
          return [];
        }
      }

      function render() {
        const query = $("searchInput").value.trim().toLocaleLowerCase();
        const status = $("statusFilter").value;
        const selectedPurok = $("purokFilter").value;
        const voter = $("voterFilter").value;
        const puroks = [...new Set(residents.map((person) => getPurok(person.address)).filter(Boolean))]
          .sort((left, right) => left.localeCompare(right, undefined, { numeric: true }));
        $("purokFilter").innerHTML = '<option value="">All puroks</option>' +
          puroks.map((purok) => `<option value="${escapeHtml(purok)}">${escapeHtml(purok)}</option>`).join("");
        if (puroks.includes(selectedPurok)) $("purokFilter").value = selectedPurok;
        const activePurok = $("purokFilter").value.toLocaleLowerCase();
        const filtered = residents.filter((person) => {
          const searchable = [person.name, person.id, person.phone, person.email, person.address, person.household];
          const matchesSearch = searchable.some((value) => String(value || "").toLocaleLowerCase().includes(query));
          const matchesPurok = !activePurok || getPurok(person.address).toLocaleLowerCase() === activePurok;
          return matchesSearch &&
            (!status || person.status === status) &&
            matchesPurok &&
            (!voter || person.voter === voter);
        });
        const pageCount = Math.max(1, Math.ceil(filtered.length / pageSize));
        currentPage = Math.min(currentPage, pageCount);
        const startIndex = (currentPage - 1) * pageSize;
        const visibleResidents = filtered.slice(startIndex, startIndex + pageSize);

        $("residentRows").innerHTML = visibleResidents.map((person) => `
          <tr>
            <td><div class="resident-name">${escapeHtml(person.name || "Unnamed resident")}</div><div class="resident-id">${escapeHtml(person.id || "No ID")}</div></td>
            <td>${escapeHtml(person.phone || "—")}<div class="resident-detail">${escapeHtml(person.email || "")}</div></td>
            <td>${escapeHtml(person.address || "—")}</td>
            <td>${escapeHtml(person.household || "—")}</td>
            <td>${person.voter === "Yes" ? "Yes" : "No"}</td>
            <td><span class="status ${escapeHtml(String(person.status || "").toLowerCase())}">${escapeHtml(person.status || "Unknown")}</span></td>
          </tr>`).join("");
        $("emptyState").hidden = filtered.length > 0;
        $("emptyState").textContent = residents.length
          ? "No matching residents. Adjust your search or filters."
          : "No resident records found. Use the Overview page to add residents or load sample data.";
        $("recordCount").textContent = filtered.length
          ? `Showing ${startIndex + 1}–${Math.min(startIndex + pageSize, filtered.length)} of ${filtered.length} matching resident${filtered.length === 1 ? "" : "s"} (${residents.length} total)`
          : `Showing 0 matching residents (${residents.length} total)`;
        $("pageIndicator").textContent = `Page ${currentPage} of ${pageCount}`;
        $("previousPage").disabled = currentPage === 1;
        $("nextPage").disabled = currentPage === pageCount;
      }

      $("todayLabel").textContent = new Intl.DateTimeFormat("en-PH", { dateStyle: "medium" }).format(new Date());
      residents = loadResidents();
      $("searchInput").addEventListener("input", () => { currentPage = 1; render(); });
      $("statusFilter").addEventListener("change", () => { currentPage = 1; render(); });
      $("purokFilter").addEventListener("change", () => { currentPage = 1; render(); });
      $("voterFilter").addEventListener("change", () => { currentPage = 1; render(); });
      $("pageSize").addEventListener("change", () => { pageSize = Number($("pageSize").value); currentPage = 1; render(); });
      $("previousPage").addEventListener("click", () => { currentPage = Math.max(1, currentPage - 1); render(); });
      $("nextPage").addEventListener("click", () => { currentPage++; render(); });
      window.addEventListener("storage", (event) => {
        if (event.key === STORAGE_KEY || event.key === null) {
          residents = loadResidents();
          render();
        }
      });
      render();
    })();
  </script>
</body>
</html>