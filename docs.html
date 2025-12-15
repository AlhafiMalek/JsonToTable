<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>JsonToTable Documentation (v3.6)</title>

  <!-- Bootstrap 5 -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Font Awesome (optional, for icons) -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">

  <style>
    body { background: #f7f7fb; }
    .doc-shell { max-width: 1100px; }
    .doc-card { border: 0; border-radius: 16px; box-shadow: 0 6px 20px rgba(0,0,0,.06); }
    .doc-title { letter-spacing: -.02em; }
    .code {
      background: #0b1220;
      color: #e7ecff;
      border-radius: 14px;
      padding: 14px 16px;
      overflow: auto;
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
      font-size: .92rem;
      line-height: 1.35rem;
    }
    .badge-soft {
      background: rgba(13,110,253,.12);
      color: #0d6efd;
      border: 1px solid rgba(13,110,253,.18);
    }
    .nav-pills .nav-link { border-radius: 12px; }
    .k { font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace; }
    .toc a { text-decoration: none; }
    .toc a:hover { text-decoration: underline; }
    .muted { color: #6c757d; }
    .section-title { scroll-margin-top: 80px; }
    .hr-soft { border-top: 1px solid rgba(0,0,0,.08); }
  </style>
</head>

<body>
  <nav class="navbar navbar-expand-lg bg-white border-bottom sticky-top">
    <div class="container doc-shell">
      <a class="navbar-brand fw-semibold" href="#top">
        <i class="fa-solid fa-table me-2"></i>JsonToTable
        <span class="badge badge-soft ms-2">v3.6</span>
      </a>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navDocs">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navDocs">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="examples.html"><b>Examples</b></a></li>
          <li class="nav-item"><a class="nav-link" href="#quick-start">Quick Start</a></li>
          <li class="nav-item"><a class="nav-link" href="#config">Config</a></li>
          <li class="nav-item"><a class="nav-link" href="#columns">Columns</a></li>
          <li class="nav-item"><a class="nav-link" href="#filters">Filters</a></li>
          <li class="nav-item"><a class="nav-link" href="#sorting">Sorting</a></li>
          <li class="nav-item"><a class="nav-link" href="#export">CSV Export</a></li>
          <li class="nav-item"><a class="nav-link" href="#state">State</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <main class="container doc-shell py-4" id="top">
    <div class="row g-4">
      <!-- TOC -->
      <aside class="col-12 col-lg-3">
        <div class="card doc-card p-3">
          <div class="d-flex align-items-center justify-content-between">
            <div class="fw-semibold">Contents</div>
            <span class="muted small">HTML Docs</span>
          </div>
          <hr class="hr-soft my-3">
          <div class="toc small d-grid gap-2">
            <a href="#overview">Overview</a>
            <a href="#requirements">Requirements</a>
            <a href="#quick-start">Quick Start</a>
            <a href="#api">Public API</a>
            <a href="#config">Configuration</a>
            <a href="#columns">Columns</a>
            <a href="#render">Render Modes</a>
            <a href="#filters">Filters</a>
            <a href="#search">Global Search</a>
            <a href="#sorting">Sorting</a>
            <a href="#paging">Paging</a>
            <a href="#actions">Actions</a>
            <a href="#export">CSV Export</a>
            <a href="#state">Local Storage State</a>
            <a href="#tips">Performance Tips</a>
          </div>
        </div>
      </aside>

      <!-- CONTENT -->
      <section class="col-12 col-lg-9">
        <!-- HERO -->
        <div class="card doc-card p-4">
          <div class="d-flex flex-wrap align-items-start justify-content-between gap-3">
            <div>
              <h1 class="doc-title fw-bold mb-1">JsonToTable Documentation</h1>
              <div class="muted">
                Interactive Bootstrap table from JSON with filters, sorting, paging, and CSV export.
              </div>
            </div>
            <div class="text-end">
              <div class="small muted">Created by</div>
              <div class="fw-semibold">Malek Alhafi</div>
              <div class="small"><a href="https://www.malekalhafi.com" target="_blank" rel="noopener">www.MalekAlhafi.com</a></div>
            </div>
          </div>

          <hr class="hr-soft my-4">

          <div class="row g-3">
            <div class="col-12 col-md-6">
              <div class="p-3 bg-light rounded-4">
                <div class="fw-semibold mb-1"><i class="fa-solid fa-check me-2"></i>Features</div>
                <ul class="mb-0 small">
                  <li>Auto columns or custom columns</li>
                  <li>Modal filters (checkbox / radio / text / sign / number-range / date-range)</li>
                  <li>Global search (AND words + exclude with <span class="k">-word</span>)</li>
                  <li>Header sorting (ASC / DESC / clear)</li>
                  <li>Pagination with page size</li>
                  <li>CSV export icon in footer (center)</li>
                  <li>State save/restore via localStorage</li>
                </ul>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="p-3 bg-light rounded-4">
                <div class="fw-semibold mb-1"><i class="fa-solid fa-circle-info me-2"></i>Notes</div>
                <ul class="mb-0 small">
                  <li>Bootstrap 5 is required for the filter modal.</li>
                  <li>FontAwesome is optional for icons.</li>
                  <li>Action column is always non-sortable.</li>
                  <li>Sorting applies after filters + global search.</li>
                </ul>
              </div>
            </div>
          </div>
        </div>

        <!-- OVERVIEW -->
        <div class="card doc-card p-4 mt-4" id="overview">
          <h2 class="section-title fw-bold h4 mb-3">Overview</h2>
          <p class="mb-0">
            <span class="k">JsonToTable</span> renders a responsive table from an array of objects (or from a JSON API),
            then provides built-in filtering, searching, sorting, paging, and CSV export — with a simple fluent API.
          </p>
        </div>

        <!-- REQUIREMENTS -->
        <div class="card doc-card p-4 mt-4" id="requirements">
          <h2 class="section-title fw-bold h4 mb-3">Requirements</h2>

          <div class="row g-3">
            <div class="col-12 col-md-6">
              <div class="p-3 border rounded-4 bg-white">
                <div class="fw-semibold mb-2">Required</div>
                <ul class="small mb-0">
                  <li>Bootstrap 5 CSS</li>
                  <li>Bootstrap 5 JS bundle (modal behavior)</li>
                </ul>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="p-3 border rounded-4 bg-white">
                <div class="fw-semibold mb-2">Optional</div>
                <ul class="small mb-0">
                  <li>FontAwesome (icons)</li>
                </ul>
              </div>
            </div>
          </div>

          <div class="mt-3">
            <div class="code"><pre class="mb-0"><code>&lt;!-- Bootstrap 5 --&gt;
&lt;link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"&gt;
&lt;script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"&gt;&lt;/script&gt;

&lt;!-- FontAwesome (optional) --&gt;
&lt;link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"&gt;</code></pre></div>
          </div>
        </div>

        <!-- QUICK START -->
        <div class="card doc-card p-4 mt-4" id="quick-start">
          <h2 class="section-title fw-bold h4 mb-3">Quick Start</h2>

          <div class="fw-semibold mb-2">1) Load local data</div>
          <div class="code mb-3"><pre class="mb-0"><code>new JsonToTable("grid1").load(arrayOfObjects);</code></pre></div>

          <div class="fw-semibold mb-2">2) Fetch from API</div>
          <div class="code mb-3"><pre class="mb-0"><code>new JsonToTable("grid1").fetch("/api/list");</code></pre></div>

          <div class="fw-semibold mb-2">3) With configuration</div>
          <div class="code"><pre class="mb-0"><code>new JsonToTable("grid1")
  .config({
    pageSize: 50,
    ui: { SearchBar: true, FilterButton: true, ExportCSV: true },
    initialSort: { key: "TIME", dir: "desc" },
    columns: [
      { key: "ID", label: "ID", sortable: true },
      { key: "DESCRIPTION", label: "Description", filter: { type: "text" } },
      { key: "AMOUNT", label: "Amount", render: "money", filter: { type: "number-range" } },
      { key: "TIME", label: "Time", render: "unixSecondsToLocal", filter: { type: "date-range" } },
      { key: "COMMENTS", label: "Comments", sortable: false } // disable sort
    ],
    actions: {
      idKey: "ID",
      view: (row) =&gt; `/view?id=${row.ID}`,
      edit: (row) =&gt; `/edit?id=${row.ID}`,
      delete: async (row) =&gt; console.log("delete", row.ID),
    }
  })
  .fetch("/core/api/1.0/transaction.php?action=GetAll");</code></pre></div>
        </div>

        <!-- PUBLIC API -->
        <div class="card doc-card p-4 mt-4" id="api">
          <h2 class="section-title fw-bold h4 mb-3">Public API</h2>

          <div class="row g-3">
            <div class="col-12">
              <div class="p-3 bg-light rounded-4">
                <div class="d-flex flex-wrap gap-2">
                  <span class="badge text-bg-dark">config(cfg)</span>
                  <span class="badge text-bg-dark">load(data)</span>
                  <span class="badge text-bg-dark">fetch(url)</span>
                  <span class="badge text-bg-dark">applyFilters()</span>
                  <span class="badge text-bg-dark">resetFilters()</span>
                  <span class="badge text-bg-dark">exportCSV(name, onlyFiltered)</span>
                  <span class="badge text-bg-dark">onFiltered(fn)</span>
                </div>
                <div class="small mt-2 muted">
                  Methods are chainable where applicable (fluent API style).
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- CONFIG -->
        <div class="card doc-card p-4 mt-4" id="config">
          <h2 class="section-title fw-bold h4 mb-3">Configuration</h2>

          <div class="row g-3">
            <div class="col-12 col-md-6">
              <div class="p-3 border rounded-4 bg-white">
                <div class="fw-semibold mb-2">Top Level</div>
                <ul class="small mb-0">
                  <li><span class="k">pageSize</span> (number) default: 25</li>
                  <li><span class="k">title</span> (string) modal title</li>
                  <li><span class="k">storageKey</span> (string) localStorage key</li>
                  <li><span class="k">initialSort</span> (object|null) default sort</li>
                  <li><span class="k">columns</span> (array|null) columns definition</li>
                  <li><span class="k">actions</span> (object|null) view/edit/delete</li>
                </ul>
              </div>
            </div>

            <div class="col-12 col-md-6">
              <div class="p-3 border rounded-4 bg-white">
                <div class="fw-semibold mb-2">UI</div>
                <ul class="small mb-0">
                  <li><span class="k">ui.SearchBar</span> (bool) default: true</li>
                  <li><span class="k">ui.FilterButton</span> (bool) default: true</li>
                  <li><span class="k">ui.ExportCSV</span> (bool) default: true</li>
                </ul>
              </div>
            </div>
          </div>

          <div class="mt-3">
            <div class="code"><pre class="mb-0"><code>.config({
  pageSize: 25,
  title: "Filter",
  storageKey: "JsonToTable_grid1",
  ui: { SearchBar: true, FilterButton: true, ExportCSV: true },
  initialSort: { key: "TIME", dir: "desc" }
})</code></pre></div>
          </div>
        </div>

        <!-- COLUMNS -->
        <div class="card doc-card p-4 mt-4" id="columns">
          <h2 class="section-title fw-bold h4 mb-3">Columns</h2>

          <p class="mb-3">
            Each column describes how to read, label, render, filter, and sort a field from the input row object.
          </p>

          <div class="p-3 border rounded-4 bg-white mb-3">
            <div class="fw-semibold mb-2">Column Schema</div>
            <div class="code"><pre class="mb-0"><code>{
  key: "FIELD_NAME",              // required
  label: "Column Title",          // optional
  render: "money" | "unixSecondsToLocal",  // optional
  filter: { type: "text" | "checkbox" | "radio" | "sign" | "number-range" | "date-range", ... }, // optional
  sortable: true | false          // optional (default true)
}</code></pre></div>
          </div>

          <div class="alert alert-info rounded-4 mb-0">
            <i class="fa-solid fa-circle-info me-2"></i>
            If <span class="k">columns</span> is not provided, keys are auto-detected from the first row.
          </div>
        </div>

        <!-- RENDER -->
        <div class="card doc-card p-4 mt-4" id="render">
          <h2 class="section-title fw-bold h4 mb-3">Render Modes</h2>

          <div class="row g-3">
            <div class="col-12 col-md-6">
              <div class="p-3 border rounded-4 bg-white">
                <div class="fw-semibold"><span class="k">money</span></div>
                <div class="small muted mb-2">Formats a number with +/-, and colors (red/green).</div>
                <div class="code"><pre class="mb-0"><code>{ key: "AMOUNT", render: "money" }</code></pre></div>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div class="p-3 border rounded-4 bg-white">
                <div class="fw-semibold"><span class="k">unixSecondsToLocal</span></div>
                <div class="small muted mb-2">Converts unix seconds to local date time.</div>
                <div class="code"><pre class="mb-0"><code>{ key: "TIME", render: "unixSecondsToLocal" }</code></pre></div>
              </div>
            </div>
          </div>
        </div>

        <!-- FILTERS -->
        <div class="card doc-card p-4 mt-4" id="filters">
          <h2 class="section-title fw-bold h4 mb-3">Filters</h2>

          <p class="mb-3">Filters appear inside a Bootstrap modal (Filter button). Each column may define a filter.</p>

          <div class="row g-3">
            <div class="col-12 col-md-6">
              <div class="p-3 border rounded-4 bg-white h-100">
                <div class="fw-semibold mb-2">Types</div>
                <ul class="small mb-0">
                  <li><span class="k">checkbox</span> (+ searchable, select all/clear)</li>
                  <li><span class="k">radio</span> (includeAll, options)</li>
                  <li><span class="k">text</span> (mode: contains/starts/exact, datalist)</li>
                  <li><span class="k">sign</span> (All/Positive/Negative)</li>
                  <li><span class="k">number-range</span> (min/max)</li>
                  <li><span class="k">date-range</span> (from/to, expects unix seconds)</li>
                </ul>
              </div>
            </div>

            <div class="col-12 col-md-6">
              <div class="p-3 border rounded-4 bg-white h-100">
                <div class="fw-semibold mb-2">Auto Filter Rules</div>
                <ul class="small mb-0">
                  <li>Unix seconds → <span class="k">date-range</span></li>
                  <li>Numeric → <span class="k">number-range</span></li>
                  <li>Other → <span class="k">text</span> with datalist</li>
                </ul>
              </div>
            </div>
          </div>

          <div class="mt-3">
            <div class="fw-semibold mb-2">Examples</div>
            <div class="code"><pre class="mb-0"><code>columns: [
  { key: "PROJECT_NAME", filter: { type: "checkbox", searchable: true } },
  { key: "STATUS", filter: { type: "radio", includeAll: true, options: ["Open","Closed"] } },
  { key: "DESCRIPTION", filter: { type: "text", datalist: true, mode: "contains" } },
  { key: "AMOUNT", filter: { type: "number-range" } },
  { key: "TIME", filter: { type: "date-range" } },
  { key: "AMOUNT", filter: { type: "sign" } }
]</code></pre></div>
          </div>
        </div>

        <!-- SEARCH -->
        <div class="card doc-card p-4 mt-4" id="search">
          <h2 class="section-title fw-bold h4 mb-3">Global Search</h2>
          <ul class="mb-3">
            <li><b>Multi-word AND</b>: <span class="k">john paid</span> → must include both words</li>
            <li><b>Exclude word</b>: <span class="k">john -paid</span> → exclude matches containing <span class="k">paid</span></li>
          </ul>
          <div class="alert alert-secondary rounded-4 mb-0">
            Search is performed on <b>rendered values</b> (money formatting and local date strings are included).
          </div>
        </div>

        <!-- SORTING -->
        <div class="card doc-card p-4 mt-4" id="sorting">
          <h2 class="section-title fw-bold h4 mb-3">Sorting</h2>
          <p class="mb-2">Click any sortable header:</p>
          <ol class="mb-3">
            <li>First click → ASC (▲)</li>
            <li>Second click → DESC (▼)</li>
            <li>Third click → Clear sort (▲▼)</li>
          </ol>

          <div class="p-3 border rounded-4 bg-white">
            <div class="fw-semibold mb-2">Disable sort per column</div>
            <div class="code"><pre class="mb-0"><code>{ key: "COMMENTS", label: "Comments", sortable: false }</code></pre></div>
            <div class="small muted mt-2">
              The Action column is always non-sortable automatically.
            </div>
          </div>
        </div>

        <!-- PAGING -->
        <div class="card doc-card p-4 mt-4" id="paging">
          <h2 class="section-title fw-bold h4 mb-3">Paging</h2>
          <ul class="mb-0">
            <li>Controlled by <span class="k">pageSize</span></li>
            <li>Filtering/search resets to page 1 automatically</li>
          </ul>
        </div>

        <!-- ACTIONS -->
        <div class="card doc-card p-4 mt-4" id="actions">
          <h2 class="section-title fw-bold h4 mb-3">Actions</h2>
          <p class="mb-3">Optional view/edit/delete buttons per row.</p>

          <div class="p-3 border rounded-4 bg-white">
            <div class="fw-semibold mb-2">Example</div>
            <div class="code"><pre class="mb-0"><code>actions: {
  idKey: "ID",
  view: (row) =&gt; `/view?id=${row.ID}`,
  edit: (row) =&gt; `/edit?id=${row.ID}`,
  delete: async (row) =&gt; {
    if (!confirm("Delete this record?")) return;
    await apiDelete(row.ID);
  }
}</code></pre></div>

            <div class="alert alert-warning rounded-4 mt-3 mb-0">
              <i class="fa-solid fa-triangle-exclamation me-2"></i>
              If any action is used, <span class="k">actions.idKey</span> is required.
            </div>
          </div>
        </div>

        <!-- EXPORT -->
        <div class="card doc-card p-4 mt-4" id="export">
          <h2 class="section-title fw-bold h4 mb-3">CSV Export</h2>

          <div class="p-3 border rounded-4 bg-white mb-3">
            <div class="fw-semibold mb-2">UI Placement</div>
            <div class="small muted">
              The export icon button is placed <b>between</b> the page counter and the paging buttons (center).
            </div>
          </div>

          <div class="row g-3">
            <div class="col-12 col-md-6">
              <div class="p-3 border rounded-4 bg-white h-100">
                <div class="fw-semibold mb-2">Button</div>
                <div class="code"><pre class="mb-0"><code>&lt;i class="btn btn-success btn-sm"&gt;
  &lt;i class="fas fa-download"&gt;&lt;/i&gt;
&lt;/i&gt;</code></pre></div>
              </div>
            </div>

            <div class="col-12 col-md-6">
              <div class="p-3 border rounded-4 bg-white h-100">
                <div class="fw-semibold mb-2">Behavior</div>
                <ul class="small mb-0">
                  <li>Click → export <b>Filtered</b></li>
                  <li>Shift + Click → export <b>All</b></li>
                  <li>CSV includes UTF-8 BOM for Excel support</li>
                </ul>
              </div>
            </div>
          </div>
        </div>

        <!-- STATE -->
        <div class="card doc-card p-4 mt-4" id="state">
          <h2 class="section-title fw-bold h4 mb-3">Local Storage State</h2>
          <p class="mb-3">Automatically saved and restored:</p>
          <ul class="mb-3">
            <li>Global search text</li>
            <li>All filter selections/inputs</li>
            <li>Current sort column + direction</li>
          </ul>

          <div class="p-3 border rounded-4 bg-white">
            <div class="fw-semibold mb-2">Reset</div>
            <ul class="small mb-0">
              <li>Use the modal <b>Reset</b> button, or call <span class="k">resetFilters()</span></li>
            </ul>
          </div>
        </div>

        <!-- TIPS -->
        <div class="card doc-card p-4 mt-4" id="tips">
          <h2 class="section-title fw-bold h4 mb-3">Performance Tips (Large Datasets)</h2>
          <ul class="mb-0">
            <li>Use smaller <span class="k">pageSize</span> for faster UI refresh.</li>
            <li>Disable heavy filters on huge text columns if not needed.</li>
            <li>Disable sorting for columns that don’t need it: <span class="k">sortable: false</span>.</li>
            <li>If your API returns very large lists, consider server-side paging and filtering.</li>
          </ul>
        </div>

        <div class="text-center small muted mt-4">
          JsonToTable v3.6 — Documentation Page
        </div>
      </section>
    </div>
  </main>

  <!-- Bootstrap 5 JS bundle -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
