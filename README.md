<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="referrer" content="no-referrer">
<meta http-equiv="Content-Security-Policy" content="default-src 'none'; script-src 'unsafe-inline' 'unsafe-eval' 'wasm-unsafe-eval' blob: data: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://esm.sh https://fonts.bunny.net https://fonts.googleapis.com https://fonts.gstatic.com https://unpkg.com; style-src 'unsafe-inline' blob: data: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://esm.sh https://fonts.bunny.net https://fonts.googleapis.com https://fonts.gstatic.com https://unpkg.com; img-src blob: data: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://esm.sh https://fonts.bunny.net https://fonts.googleapis.com https://fonts.gstatic.com https://unpkg.com; font-src blob: data: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://esm.sh https://fonts.bunny.net https://fonts.googleapis.com https://fonts.gstatic.com https://unpkg.com; media-src blob: data: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://esm.sh https://fonts.bunny.net https://fonts.googleapis.com https://fonts.gstatic.com https://unpkg.com; worker-src blob:; connect-src blob: data:; frame-src 'self'; object-src 'none'; base-uri 'none'; form-action 'none'">
<title>Monthly Data Collection</title>
<style>:root{color-scheme:light dark;background:light-dark(rgb(255 255 255), rgb(24 24 24))}html,body{margin:0}body{box-sizing:border-box;padding:1rem;background:inherit}iframe{display:block;width:100%;max-width:736px;height:calc(100vh - 2rem);margin:0 auto;border:0}</style>
</head>
<body>
<iframe sandbox="allow-scripts" referrerpolicy="no-referrer" title="Monthly Data Collection" srcdoc="&lt;!doctype html&gt;
&lt;html lang=&quot;en&quot;&gt;
&lt;head&gt;
&lt;meta charset=&quot;utf-8&quot;&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1&quot;&gt;
&lt;meta name=&quot;referrer&quot; content=&quot;no-referrer&quot;&gt;
&lt;meta http-equiv=&quot;Content-Security-Policy&quot; content=&quot;default-src &#x27;none&#x27;; script-src &#x27;unsafe-inline&#x27; &#x27;unsafe-eval&#x27; &#x27;wasm-unsafe-eval&#x27; blob: data: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://esm.sh https://fonts.bunny.net https://fonts.googleapis.com https://fonts.gstatic.com https://unpkg.com; style-src &#x27;unsafe-inline&#x27; blob: data: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://esm.sh https://fonts.bunny.net https://fonts.googleapis.com https://fonts.gstatic.com https://unpkg.com; img-src blob: data: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://esm.sh https://fonts.bunny.net https://fonts.googleapis.com https://fonts.gstatic.com https://unpkg.com; font-src blob: data: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://esm.sh https://fonts.bunny.net https://fonts.googleapis.com https://fonts.gstatic.com https://unpkg.com; media-src blob: data: https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://esm.sh https://fonts.bunny.net https://fonts.googleapis.com https://fonts.gstatic.com https://unpkg.com; worker-src blob:; connect-src blob: data:; frame-src &#x27;none&#x27;; object-src &#x27;none&#x27;; base-uri &#x27;none&#x27;; form-action &#x27;none&#x27;&quot;&gt;
&lt;title&gt;Monthly Data Collection&lt;/title&gt;
&lt;style&gt;:root {
  color-scheme: light dark;
  background-color: var(--background) !important;

  /* Agent-facing contract; keep in sync with SKILL.md. */
  --background: light-dark(rgb(255 255 255), rgb(24 24 24));
  --foreground: light-dark(rgb(26 28 31), rgb(255 255 255));
  --card: color-mix(in oklab, var(--foreground) 5%, transparent);
  --card-foreground: var(--foreground);
  --popover: light-dark(rgb(255 255 255), rgb(45 45 45));
  --popover-foreground: var(--foreground);
  --primary: light-dark(rgb(51 156 255), rgb(131 195 255));
  --primary-foreground: light-dark(rgb(255 255 255), rgb(13 13 13));
  --secondary: light-dark(rgb(255 255 255 / 96%), rgb(54 54 54 / 96%));
  --secondary-foreground: var(--foreground);
  --muted: color-mix(in srgb, var(--foreground) 10%, transparent);
  --muted-foreground: light-dark(
    rgb(26 28 31 / 49.4%),
    rgb(255 255 255 / 49.8%)
  );
  --accent: light-dark(rgb(229 242 255), rgb(13 39 63));
  --accent-foreground: var(--primary);
  --destructive: light-dark(rgb(226 85 7), rgb(255 133 73));
  --border: light-dark(rgb(26 28 31 / 8%), rgb(255 255 255 / 8.2%));
  --input: light-dark(
    rgb(26 28 31 / 11.8%),
    color-mix(in oklab, rgb(0 0 0) 10%, transparent)
  );
  --ring: light-dark(rgb(51 156 255), rgb(131 195 255 / 76%));
  --font-size-base: 14px;
  --viz-series-1: var(--primary);
  --viz-series-2: light-dark(rgb(243 136 59), rgb(245 154 86));
  --viz-series-3: light-dark(rgb(93 201 119), rgb(116 213 139));
  --viz-series-4: light-dark(rgb(235 119 177), rgb(240 143 192));
  --viz-series-5: light-dark(rgb(155 121 236), rgb(170 145 239));
  --viz-series-6: light-dark(rgb(58 185 177), rgb(90 203 194));

  /* Internal implementation variables; not part of the agent contract. */
  --font-sans: -apple-system, system-ui, &quot;Segoe UI&quot;, sans-serif;
  --font-mono:
    ui-monospace, SFMono-Regular, &quot;SF Mono&quot;, Menlo, Consolas, &quot;Liberation Mono&quot;,
    monospace;
  --font-size-normal: max(11px, var(--font-size-base));
  --font-size-tooltip: calc(var(--font-size-base) - 1px);
  --font-size-small: max(11px, calc(var(--font-size-base) - 2px));
  --font-size-h1: calc(var(--font-size-normal) * 1.7142857143);
  --font-size-h2: calc(var(--font-size-normal) * 1.4285714286);
  --font-size-h3: calc(var(--font-size-normal) * 1.2857142857);
  --font-weight-normal: 430;
  --font-weight-medium: 500;
  --line-height-normal: calc(var(--font-size-normal) * 1.5);
  --line-height-tooltip: calc(var(--font-size-tooltip) * 1.4285714286);
  --line-height-small: calc(var(--font-size-small) + 4px);
  --radius: 12.5px;
  --radius-sm: calc(var(--radius) * 0.6);
  --radius-md: calc(var(--radius) * 0.8);
  --radius-lg: var(--radius);
  --radius-2xl: calc(var(--radius) * 1.6);
  --radius-full: 9999px;
  --shadow-sm: 0 1px 2px -1px rgb(0 0 0 / 8%);
  --checkmark-image: url(&quot;data:image/svg+xml,%3Csvg xmlns=&#x27;http://www.w3.org/2000/svg&#x27; viewBox=&#x27;0 0 17 17&#x27;%3E%3Cpath d=&#x27;M12.8961 3.64101C13.1297 3.41418 13.4984 3.37523 13.7779 3.56581C14.0571 3.75635 14.1554 4.11331 14.0299 4.41347L13.9615 4.53847L7.71151 13.7045C7.59411 13.8767 7.4063 13.9877 7.19881 14.0072C6.99136 14.0267 6.78564 13.9533 6.63826 13.806L2.88826 10.056L2.79842 9.9457C2.6192 9.67407 2.64927 9.30496 2.88826 9.06581C3.12738 8.82669 3.49647 8.79676 3.76815 8.97597L3.8785 9.06581L7.03084 12.2182L12.8053 3.74941L12.8961 3.64101Z&#x27;/%3E%3C/svg%3E&quot;);

  /* Legacy aliases; not part of the current agent contract. */
  --viz-bg: transparent;
  --viz-panel: var(--card);
  --viz-border: var(--border);
  --viz-text: var(--foreground);
  --viz-muted: var(--muted-foreground);
  --viz-accent: var(--primary);
  --viz-accent-text: var(--primary-foreground);
  --viz-accent-bg: var(--accent);
  --viz-font-size: var(--font-size-base);
  --viz-warning: var(--destructive);
  --color-background-primary: var(--background);
  --color-text-primary: var(--foreground);
  --color-border-secondary: var(--border);
}

:root[data-theme=&quot;light&quot;] {
  color-scheme: light;
}

:root[data-theme=&quot;dark&quot;] {
  color-scheme: dark;
}

* {
  box-sizing: border-box;
}

html &gt; body {
  margin: 0;
  padding: 5px;
  color: var(--foreground);
  background: transparent !important;
  font-family: var(--font-sans);
  font-size: var(--font-size-normal);
  font-weight: var(--font-weight-normal);
  line-height: var(--line-height-normal);
}

a {
  color: color-mix(in srgb, var(--viz-accent) 80%, var(--viz-text) 20%);
  cursor: pointer;
  font-weight: var(--viz-font-weight-medium);
  text-decoration: none;
  text-underline-offset: 2px;
}

a:is(:hover, :focus-visible) {
  text-decoration-line: underline;
  text-decoration-style: dashed;
  text-decoration-thickness: 0.5px;
}

h1,
h2,
h3,
h4,
h5,
h6,
p {
  margin-block: 0;
}

h1 {
  font-size: var(--font-size-h1);
  font-weight: var(--font-weight-medium);
  line-height: 1.25;
}

h2 {
  font-size: var(--font-size-h2);
  font-weight: var(--font-weight-medium);
  line-height: 1.25;
}

h3,
h4,
h5,
h6 {
  font-size: var(--font-size-h3);
  font-weight: var(--font-weight-medium);
  line-height: 1.3;
}

b,
strong,
th {
  font-weight: var(--font-weight-medium);
}

code:not(pre code) {
  display: inline;
  padding: 1px 6px;
  border-radius: var(--radius-sm);
  corner-shape: superellipse(1.5);
  background: var(--muted);
  font-family: var(--font-mono);
  font-size: 0.92em;
  overflow-wrap: anywhere;
  -webkit-box-decoration-break: clone;
  box-decoration-break: clone;
  word-break: break-word;
}

#widget {
  display: flex;
  flex-direction: column;
  gap: 12px;
  width: 100%;
  padding: 0;
  background: transparent !important;
}

.card {
  min-width: 0;
  padding: 12px;
  overflow: hidden;
  overflow-wrap: break-word;
  border-radius: var(--radius-2xl);
  corner-shape: superellipse(1.5);
  color: var(--card-foreground);
  background: var(--card);
}

#widget &gt; :not(.card) {
  width: 100% !important;
  max-width: none !important;
  margin: 0 !important;
  padding: 0 !important;
  border: 0 !important;
  border-radius: 0 !important;
  background: transparent !important;
  box-shadow: none !important;
}

.tooltip {
  position: fixed;
  z-index: 50;
  top: 0;
  left: 0;
  width: max-content;
  max-width: min(
    20rem,
    var(--tooltip-available-width, calc(100vw - 10px)),
    calc(100vw - 10px)
  );
  max-height: min(
    var(--tooltip-available-height, calc(100vh - 10px)),
    calc(100vh - 10px)
  );
  padding: 4px 8px;
  border: 1px solid var(--border);
  border-radius: var(--radius-lg);
  corner-shape: superellipse(1.5);
  color: var(--popover-foreground);
  background: var(--popover);
  box-shadow: none;
  font-size: var(--font-size-tooltip);
  line-height: var(--line-height-tooltip);
  overflow-wrap: break-word;
  white-space: normal;
  pointer-events: none;
  user-select: none;
}

.viz-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(max(180px, 24%), 1fr));
  gap: 10px;
}

.viz-stat {
  display: flex;
  flex-direction: column;
  gap: 2px;
}

.viz-stat-value {
  font-size: var(--font-size-h2);
  font-weight: var(--font-weight-medium);
  line-height: 1.25;
}

.viz-row {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 10px;
}

.viz-badge {
  padding: 3px 8px;
  border-radius: var(--radius-full);
  color: var(--accent-foreground);
  background: var(--accent);
  font-weight: var(--font-weight-medium);
}

small,
.text-small,
.viz-badge {
  font-size: var(--font-size-small);
  line-height: var(--line-height-small);
}

.text-muted {
  color: var(--muted-foreground);
}

.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}

.viz-controls {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 8px;
}

.viz-controls &gt; .form-label {
  display: grid;
  min-width: min(100%, 260px);
  flex: 1 1 280px;
  grid-template-columns: minmax(0, 1fr) auto;
  align-items: baseline;
  gap: 2px 12px;
  margin-bottom: 0;
}

.viz-controls &gt; .form-label &gt; :is(.form-control, .form-range, .form-select) {
  grid-column: 1 / -1;
}

.btn,
.form-check-input,
.form-control,
.form-range,
.form-select {
  font: inherit;
}

.btn {
  appearance: button;
  display: inline-flex;
  inline-size: fit-content;
  max-inline-size: 100%;
  min-height: 28px;
  align-items: center;
  justify-content: center;
  gap: 4px;
  margin: 0;
  padding: 0 8px;
  -webkit-app-region: no-drag;
  border: 1px solid var(--input);
  border-radius: var(--radius-lg);
  corner-shape: superellipse(1.5);
  color: var(--secondary-foreground);
  background: var(--secondary);
  cursor: var(--cursor-interaction, pointer);
  text-align: center;
  text-decoration: none;
  white-space: nowrap;
  user-select: none;
  -webkit-font-smoothing: antialiased;
}

.btn:is(.btn-block, .viz-tile) {
  inline-size: 100%;
}

.btn.viz-tile {
  min-width: 0;
  overflow-wrap: anywhere;
  white-space: normal;
}

a.btn {
  cursor: pointer;
  text-decoration: none;
}

.btn:not(:disabled):hover {
  background: color-mix(in srgb, var(--foreground) 6%, var(--secondary));
}

.btn-primary {
  border-color: transparent;
  color: var(--primary-foreground);
  background: var(--foreground);
  background-clip: padding-box;
}

.btn-primary .text-muted {
  color: color-mix(in srgb, var(--primary-foreground) 50%, transparent);
}

.btn-primary:not(:disabled):hover {
  background: color-mix(in srgb, var(--foreground) 80%, transparent);
  background-clip: padding-box;
}

.btn-ghost {
  border-color: transparent;
  color: var(--muted-foreground);
  background: transparent;
}

.btn-ghost:not(:disabled):hover {
  color: var(--foreground);
  background: color-mix(in srgb, var(--foreground) 6%, var(--secondary));
}

.btn:disabled {
  cursor: not-allowed;
  opacity: 0.4;
}

[data-lucide] {
  stroke-width: 1.6;
}

.form-label {
  display: block;
  margin-bottom: 6px;
  color: var(--foreground);
}

.form-control {
  display: block;
  width: 100%;
  min-height: 28px;
  padding: 0 8px;
  outline: none;
  border: 1px solid var(--input);
  border-radius: var(--radius-lg);
  corner-shape: superellipse(1.5);
  color: var(--foreground);
  background: var(--secondary);
}

.form-control::placeholder {
  color: var(--muted-foreground);
}

.form-control[type=&quot;file&quot;] {
  padding: 0;
  overflow: hidden;
  cursor: var(--cursor-interaction, pointer);
}

.form-control[type=&quot;file&quot;]::file-selector-button {
  min-height: 26px;
  margin-right: 8px;
  padding: 0 8px;
  border: 0;
  border-right: 1px solid var(--input);
  color: var(--secondary-foreground);
  background: var(--secondary);
  cursor: inherit;
  font: inherit;
}

.form-control[type=&quot;file&quot;]:not(:disabled):hover::file-selector-button {
  background: color-mix(in srgb, var(--foreground) 6%, var(--secondary));
}

.form-control-color[type=&quot;color&quot;] {
  width: 40px;
  height: 28px;
  padding: 3px;
  cursor: var(--cursor-interaction, pointer);
}

.form-control-color[type=&quot;color&quot;]::-webkit-color-swatch-wrapper {
  padding: 0;
}

.form-control-color[type=&quot;color&quot;]::-webkit-color-swatch {
  border: 0;
  border-radius: calc(var(--radius-lg) - 4px);
  corner-shape: superellipse(1.5);
}

textarea.form-control {
  height: auto;
  min-height: 72px;
  padding: 8px 10px;
  resize: vertical;
}

.form-control:focus-visible {
  border-color: var(--ring);
  box-shadow: inset 0 0 0 1px var(--ring);
}

.form-control:disabled,
.form-select:disabled {
  cursor: not-allowed;
  opacity: 0.4;
}

.form-select {
  appearance: none;
  display: block;
  width: 100%;
  min-height: 28px;
  margin: 0;
  padding: 0 32px 0 8px;
  outline: none;
  border: 1px solid var(--input);
  border-radius: var(--radius-lg);
  corner-shape: superellipse(1.5);
  color: var(--foreground);
  background-color: var(--secondary);
  background-image:
    linear-gradient(45deg, transparent 50%, var(--muted-foreground) 50%),
    linear-gradient(135deg, var(--muted-foreground) 50%, transparent 50%);
  background-position:
    calc(100% - 14px) 50%,
    calc(100% - 10px) 50%;
  background-repeat: no-repeat;
  background-size: 4px 4px;
  cursor: var(--cursor-interaction, default);
}

.form-select:not(:disabled):hover {
  background-color: color-mix(in srgb, var(--foreground) 6%, var(--secondary));
}

.form-select:focus-visible {
  border-color: var(--ring);
  box-shadow: inset 0 0 0 1px var(--ring);
}

.form-check {
  display: flex;
  min-height: 20px;
  align-items: center;
  gap: 6px;
}

.form-check-input {
  appearance: none;
  width: 14px;
  height: 14px;
  flex: 0 0 auto;
  margin: 0;
  border: 1px solid var(--input);
  color: var(--primary-foreground);
  background-color: transparent;
  cursor: var(--cursor-interaction, default);
  transition:
    background-color 150ms,
    border-color 150ms,
    box-shadow 150ms;
}

.form-check:not(.form-switch) .form-check-input[type=&quot;checkbox&quot;] {
  border-color: var(--input);
  border-radius: var(--radius-sm);
  corner-shape: superellipse(1.5);
  background-color: var(--secondary);
  box-shadow: var(--shadow-sm);
}

.form-check:not(.form-switch)
  .form-check-input:not(:disabled):not(:checked):hover {
  background-color: var(--card);
}

.form-check:not(.form-switch) .form-check-input[type=&quot;checkbox&quot;]:checked {
  border-color: var(--primary);
  background-color: var(--primary);
}

.form-check:not(.form-switch)
  .form-check-input[type=&quot;checkbox&quot;]:checked::before {
  display: block;
  width: 100%;
  height: 100%;
  background: var(--primary-foreground);
  content: &quot;&quot;;
  mask: var(--checkmark-image) center / 12px 12px no-repeat;
}

.form-check-input[type=&quot;radio&quot;] {
  width: 14px;
  height: 14px;
  border-radius: var(--radius-full);
}

.form-check-input[type=&quot;radio&quot;]:checked {
  border: 2px solid var(--primary);
  background:
    radial-gradient(circle, var(--primary-foreground) 0 2.5px, transparent 3px),
    var(--primary);
}

.form-check:not(.form-switch) .form-check-input:focus-visible {
  outline: 2px solid var(--ring);
  outline-offset: 2px;
}

.form-check:not(.form-switch) .form-check-input:disabled {
  cursor: not-allowed;
  pointer-events: none;
}

.form-check:not(.form-switch) .form-check-input:disabled + .form-check-label {
  cursor: not-allowed;
}

.form-switch .form-check-input:disabled,
.form-switch .form-check-input:disabled + .form-check-label {
  cursor: not-allowed;
  opacity: 0.6;
}

.form-check-label {
  color: var(--foreground);
  cursor: var(--cursor-interaction, default);
}

.form-switch .form-check-input {
  position: relative;
  width: 32px;
  height: 20px;
  border: 0;
  border-radius: var(--radius-full);
  background: var(--muted);
  box-shadow: none;
  transition: background-color 200ms cubic-bezier(0, 0, 0.2, 1);
}

.form-switch .form-check-input::before {
  position: absolute;
  top: 50%;
  left: 0;
  width: 16px;
  height: 16px;
  box-sizing: border-box;
  border: 1px solid light-dark(var(--primary-foreground), var(--foreground));
  border-radius: var(--radius-full);
  background: light-dark(var(--primary-foreground), var(--foreground));
  box-shadow: var(--shadow-sm);
  content: &quot;&quot;;
  transform: translate(2px, -50%);
  transition: transform 200ms cubic-bezier(0, 0, 0.2, 1);
}

.form-switch .form-check-input:checked {
  background: var(--primary);
}

.form-switch .form-check-input:checked::before {
  transform: translate(14px, -50%);
}

.form-switch .form-check-input:focus-visible {
  box-shadow: 0 0 0 2px var(--ring);
}

.form-range {
  appearance: none;
  display: block;
  width: 100%;
  height: 28px;
  flex: 1;
  margin: 0;
  padding: 0;
  outline: none;
  border: 0;
  accent-color: var(--primary);
  background: linear-gradient(
      color-mix(in srgb, var(--foreground) 7%, transparent),
      color-mix(in srgb, var(--foreground) 7%, transparent)
    )
    center / 100% 2px no-repeat;
}

.form-range::-webkit-slider-runnable-track {
  height: 28px;
  background: transparent;
}

.form-range::-webkit-slider-thumb {
  appearance: none;
  width: 20px;
  height: 20px;
  margin-top: 4px;
  border: 1px solid var(--border);
  border-radius: var(--radius-full);
  background: light-dark(var(--primary-foreground), var(--foreground));
}

.form-range:focus-visible::-webkit-slider-thumb {
  border-color: var(--ring);
  box-shadow: inset 0 0 0 1px var(--ring);
}

.form-range::-moz-range-track {
  height: 28px;
  background: transparent;
}

.form-range::-moz-range-thumb {
  width: 20px;
  height: 20px;
  border: 1px solid var(--border);
  border-radius: var(--radius-full);
  background: light-dark(var(--primary-foreground), var(--foreground));
}

.form-range:focus-visible::-moz-range-thumb {
  border-color: var(--ring);
  box-shadow: inset 0 0 0 1px var(--ring);
}

.form-range:disabled {
  cursor: not-allowed;
  opacity: 0.4;
}

.btn:not(.btn-primary, .viz-tile):is(
    [aria-pressed=&quot;true&quot;],
    [aria-selected=&quot;true&quot;],
    .is-selected
  ) {
  border-color: var(--primary);
  color: var(--primary-foreground);
  background: var(--primary);
}

.btn.viz-tile:is([aria-pressed=&quot;true&quot;], [aria-selected=&quot;true&quot;], .is-selected) {
  border-color: var(--primary);
  box-shadow: inset 0 0 0 1px var(--primary);
}

.btn:focus-visible {
  outline: 2px solid var(--ring);
  outline-offset: 2px;
}

svg {
  display: block;
  max-width: 100%;
  height: auto;
}

#widget &gt; svg {
  width: 100%;
}

.text-warning,
.text-destructive {
  color: var(--destructive);
}

html&gt;body{padding:0}&lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;style&gt;
  #monthly-data-collection .collection-shell { display: grid; gap: 1.25rem; }
  #monthly-data-collection .collection-heading { display: flex; justify-content: space-between; align-items: baseline; gap: 1rem; flex-wrap: wrap; }
  #monthly-data-collection .tracker-table { width: 100%; border-collapse: collapse; }
  #monthly-data-collection .tracker-table th, #monthly-data-collection .tracker-table td { padding: .65rem .35rem; text-align: left; border-bottom: 1px solid var(--border); vertical-align: middle; }
  #monthly-data-collection .tracker-table th { color: var(--muted-foreground); font-weight: 500; }
  #monthly-data-collection .tracker-table td:last-child, #monthly-data-collection .tracker-table th:last-child { text-align: right; }
  #monthly-data-collection .status-mark { display: inline-flex; align-items: center; gap: .4rem; white-space: nowrap; }
  #monthly-data-collection .status-mark::before { content: &quot;&quot;; inline-size: .55rem; block-size: .55rem; border-radius: 50%; background: var(--muted-foreground); }
  #monthly-data-collection .status-mark.is-complete::before { background: var(--viz-series-1); }
  #monthly-data-collection .status-mark.is-reminded::before { background: var(--viz-series-2); }
  #monthly-data-collection .flow-lane { list-style: none; padding: 0; margin: 0; display: grid; gap: .65rem; }
  #monthly-data-collection .flow-step { display: grid; grid-template-columns: 2.4rem minmax(0, 1fr); gap: .75rem; align-items: start; }
  #monthly-data-collection .flow-index { display: grid; place-items: center; inline-size: 2rem; block-size: 2rem; border: 1px solid var(--border); border-radius: 50%; color: var(--muted-foreground); }
  #monthly-data-collection .flow-step:not(:last-child) .flow-index { box-shadow: 0 2.75rem 0 -1.35rem var(--border); }
  #monthly-data-collection .flow-copy { padding-block: .15rem .8rem; }
  #monthly-data-collection .payload { white-space: pre-wrap; margin: 0; max-height: 13rem; overflow: auto; }
  #monthly-data-collection .empty-copy { padding: 1rem 0; }
  @media (max-width: 520px) {
    #monthly-data-collection .tracker-table thead { display: none; }
    #monthly-data-collection .tracker-table, #monthly-data-collection .tracker-table tbody, #monthly-data-collection .tracker-table tr, #monthly-data-collection .tracker-table td { display: block; width: 100%; }
    #monthly-data-collection .tracker-table tr { padding: .6rem 0; border-bottom: 1px solid var(--border); }
    #monthly-data-collection .tracker-table td { border: 0; padding: .2rem 0; text-align: left !important; }
    #monthly-data-collection .tracker-table td::before { content: attr(data-label) &quot;: &quot;; color: var(--muted-foreground); }
  }
&lt;/style&gt;

&lt;div id=&quot;monthly-data-collection&quot; class=&quot;collection-shell&quot;&gt;
  &lt;div class=&quot;collection-heading&quot;&gt;
    &lt;div&gt;
      &lt;span class=&quot;viz-badge&quot;&gt;Collection open&lt;/span&gt;
      &lt;p class=&quot;text-muted text-small&quot; id=&quot;deadline-copy&quot;&gt;July 2026 · submit by 18 July, 17:00&lt;/p&gt;
    &lt;/div&gt;
    &lt;div class=&quot;viz-controls&quot; aria-label=&quot;Collection controls&quot;&gt;
      &lt;label class=&quot;form-label&quot; for=&quot;cycle&quot;&gt;Reporting month
        &lt;select id=&quot;cycle&quot; class=&quot;form-select&quot;&gt;
          &lt;option value=&quot;July 2026&quot; selected&gt;July 2026&lt;/option&gt;
          &lt;option value=&quot;August 2026&quot;&gt;August 2026&lt;/option&gt;
          &lt;option value=&quot;September 2026&quot;&gt;September 2026&lt;/option&gt;
        &lt;/select&gt;
      &lt;/label&gt;
      &lt;label class=&quot;form-label&quot; for=&quot;due-day&quot;&gt;Due date
        &lt;input id=&quot;due-day&quot; class=&quot;form-control&quot; type=&quot;number&quot; min=&quot;1&quot; max=&quot;28&quot; value=&quot;18&quot; inputmode=&quot;numeric&quot;&gt;
      &lt;/label&gt;
      &lt;label class=&quot;form-label&quot; for=&quot;reminder-days&quot;&gt;Reminder lead time
        &lt;select id=&quot;reminder-days&quot; class=&quot;form-select&quot;&gt;
          &lt;option value=&quot;7&quot;&gt;7 days before&lt;/option&gt;
          &lt;option value=&quot;5&quot; selected&gt;5 days before&lt;/option&gt;
          &lt;option value=&quot;3&quot;&gt;3 days before&lt;/option&gt;
        &lt;/select&gt;
      &lt;/label&gt;
    &lt;/div&gt;
  &lt;/div&gt;

  &lt;div class=&quot;viz-grid&quot; aria-label=&quot;Collection progress&quot;&gt;
    &lt;section class=&quot;card viz-stat&quot; aria-label=&quot;Completed submissions&quot;&gt;
      &lt;span class=&quot;text-muted&quot;&gt;Submitted&lt;/span&gt;
      &lt;strong class=&quot;viz-stat-value&quot; id=&quot;submitted-stat&quot;&gt;2 / 5&lt;/strong&gt;
      &lt;span class=&quot;text-small&quot; id=&quot;submitted-context&quot;&gt;40% complete&lt;/span&gt;
    &lt;/section&gt;
    &lt;section class=&quot;card viz-stat&quot; aria-label=&quot;Outstanding submissions&quot;&gt;
      &lt;span class=&quot;text-muted&quot;&gt;Outstanding&lt;/span&gt;
      &lt;strong class=&quot;viz-stat-value&quot; id=&quot;outstanding-stat&quot;&gt;3&lt;/strong&gt;
      &lt;span class=&quot;text-small&quot;&gt;Owners still to respond&lt;/span&gt;
    &lt;/section&gt;
    &lt;section class=&quot;card viz-stat&quot; aria-label=&quot;Power BI status&quot;&gt;
      &lt;span class=&quot;text-muted&quot;&gt;Power BI handoff&lt;/span&gt;
      &lt;strong class=&quot;viz-stat-value&quot; id=&quot;powerbi-stat&quot;&gt;Ready&lt;/strong&gt;
      &lt;span class=&quot;text-small&quot; id=&quot;powerbi-context&quot;&gt;5 rows matched to contract&lt;/span&gt;
    &lt;/section&gt;
  &lt;/div&gt;

  &lt;section aria-labelledby=&quot;submit-heading&quot;&gt;
    &lt;div class=&quot;collection-heading&quot;&gt;
      &lt;div&gt;
        &lt;h2 id=&quot;submit-heading&quot;&gt;Submit your monthly data&lt;/h2&gt;
        &lt;p class=&quot;text-muted text-small&quot;&gt;Every required field becomes one dashboard-ready record.&lt;/p&gt;
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;form id=&quot;submission-form&quot; class=&quot;card&quot;&gt;
      &lt;div class=&quot;viz-controls&quot;&gt;
        &lt;label class=&quot;form-label&quot; for=&quot;team&quot;&gt;Team
          &lt;select id=&quot;team&quot; class=&quot;form-select&quot; required&gt;
            &lt;option value=&quot;Finance&quot;&gt;Finance&lt;/option&gt;
            &lt;option value=&quot;Operations&quot;&gt;Operations&lt;/option&gt;
            &lt;option value=&quot;People&quot;&gt;People&lt;/option&gt;
            &lt;option value=&quot;Commercial&quot;&gt;Commercial&lt;/option&gt;
            &lt;option value=&quot;Technology&quot;&gt;Technology&lt;/option&gt;
          &lt;/select&gt;
        &lt;/label&gt;
        &lt;label class=&quot;form-label&quot; for=&quot;owner&quot;&gt;Owner
          &lt;input id=&quot;owner&quot; class=&quot;form-control&quot; type=&quot;text&quot; value=&quot;Alex Morgan&quot; required&gt;
        &lt;/label&gt;
        &lt;label class=&quot;form-label&quot; for=&quot;owner-email&quot;&gt;Work email
          &lt;input id=&quot;owner-email&quot; class=&quot;form-control&quot; type=&quot;email&quot; value=&quot;alex.morgan@company.com&quot; required&gt;
        &lt;/label&gt;
        &lt;label class=&quot;form-label&quot; for=&quot;metric&quot;&gt;Actual value
          &lt;input id=&quot;metric&quot; class=&quot;form-control&quot; type=&quot;number&quot; value=&quot;125000&quot; min=&quot;0&quot; step=&quot;0.01&quot; required&gt;
        &lt;/label&gt;
        &lt;label class=&quot;form-label&quot; for=&quot;target&quot;&gt;Target value
          &lt;input id=&quot;target&quot; class=&quot;form-control&quot; type=&quot;number&quot; value=&quot;120000&quot; min=&quot;0&quot; step=&quot;0.01&quot; required&gt;
        &lt;/label&gt;
      &lt;/div&gt;
      &lt;div class=&quot;viz-controls&quot;&gt;
        &lt;label class=&quot;form-label&quot; for=&quot;note&quot;&gt;Comment / variance explanation
          &lt;textarea id=&quot;note&quot; class=&quot;form-control&quot; rows=&quot;2&quot; placeholder=&quot;What changed this month?&quot;&gt;&lt;/textarea&gt;
        &lt;/label&gt;
        &lt;button class=&quot;btn btn-primary&quot; type=&quot;submit&quot;&gt;Submit data&lt;/button&gt;
      &lt;/div&gt;
      &lt;p class=&quot;text-small&quot; id=&quot;form-status&quot; role=&quot;status&quot; aria-live=&quot;polite&quot;&gt;&lt;/p&gt;
    &lt;/form&gt;
  &lt;/section&gt;

  &lt;section aria-labelledby=&quot;tracker-heading&quot;&gt;
    &lt;div class=&quot;collection-heading&quot;&gt;
      &lt;div&gt;
        &lt;h2 id=&quot;tracker-heading&quot;&gt;Submission tracker&lt;/h2&gt;
        &lt;p class=&quot;text-muted text-small&quot; id=&quot;reminder-status&quot;&gt;The scheduled reminder will target all outstanding owners.&lt;/p&gt;
      &lt;/div&gt;
      &lt;div class=&quot;viz-row&quot;&gt;
        &lt;button id=&quot;send-reminders&quot; class=&quot;btn&quot; type=&quot;button&quot;&gt;Send reminders&lt;/button&gt;
        &lt;button id=&quot;prepare-payload&quot; class=&quot;btn btn-primary&quot; type=&quot;button&quot;&gt;Prepare Power BI payload&lt;/button&gt;
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;table class=&quot;tracker-table&quot; aria-describedby=&quot;reminder-status&quot;&gt;
      &lt;caption class=&quot;sr-only&quot;&gt;Monthly submission status by team&lt;/caption&gt;
      &lt;thead&gt;
        &lt;tr&gt;&lt;th scope=&quot;col&quot;&gt;Team&lt;/th&gt;&lt;th scope=&quot;col&quot;&gt;Owner&lt;/th&gt;&lt;th scope=&quot;col&quot;&gt;Status&lt;/th&gt;&lt;th scope=&quot;col&quot;&gt;Submitted&lt;/th&gt;&lt;/tr&gt;
      &lt;/thead&gt;
      &lt;tbody id=&quot;tracker-body&quot;&gt;&lt;/tbody&gt;
    &lt;/table&gt;
  &lt;/section&gt;

  &lt;section aria-labelledby=&quot;handoff-heading&quot;&gt;
    &lt;div class=&quot;collection-heading&quot;&gt;
      &lt;div&gt;
        &lt;h2 id=&quot;handoff-heading&quot;&gt;Power BI data flow&lt;/h2&gt;
        &lt;p class=&quot;text-muted text-small&quot;&gt;Use this contract in Power Automate or a Power BI Dataflow.&lt;/p&gt;
      &lt;/div&gt;
      &lt;span id=&quot;payload-badge&quot; class=&quot;viz-badge&quot;&gt;Awaiting next export&lt;/span&gt;
    &lt;/div&gt;
    &lt;ol class=&quot;flow-lane&quot; aria-label=&quot;Data flow from collection to dashboard&quot;&gt;
      &lt;li class=&quot;flow-step&quot;&gt;&lt;span class=&quot;flow-index&quot; aria-hidden=&quot;true&quot;&gt;1&lt;/span&gt;&lt;div class=&quot;flow-copy&quot;&gt;&lt;strong&gt;Schedule&lt;/strong&gt;&lt;br&gt;&lt;span class=&quot;text-muted text-small&quot;&gt;A monthly recurrence opens the collection and calculates the due date.&lt;/span&gt;&lt;/div&gt;&lt;/li&gt;
      &lt;li class=&quot;flow-step&quot;&gt;&lt;span class=&quot;flow-index&quot; aria-hidden=&quot;true&quot;&gt;2&lt;/span&gt;&lt;div class=&quot;flow-copy&quot;&gt;&lt;strong&gt;Remind&lt;/strong&gt;&lt;br&gt;&lt;span class=&quot;text-muted text-small&quot;&gt;Power Automate emails only owners without a completed submission at the configured lead time.&lt;/span&gt;&lt;/div&gt;&lt;/li&gt;
      &lt;li class=&quot;flow-step&quot;&gt;&lt;span class=&quot;flow-index&quot; aria-hidden=&quot;true&quot;&gt;3&lt;/span&gt;&lt;div class=&quot;flow-copy&quot;&gt;&lt;strong&gt;Store &amp;amp; validate&lt;/strong&gt;&lt;br&gt;&lt;span class=&quot;text-muted text-small&quot;&gt;The app writes validated records to SharePoint or Dataverse using the listed fields.&lt;/span&gt;&lt;/div&gt;&lt;/li&gt;
      &lt;li class=&quot;flow-step&quot;&gt;&lt;span class=&quot;flow-index&quot; aria-hidden=&quot;true&quot;&gt;4&lt;/span&gt;&lt;div class=&quot;flow-copy&quot;&gt;&lt;strong&gt;Refresh dashboard&lt;/strong&gt;&lt;br&gt;&lt;span class=&quot;text-muted text-small&quot;&gt;A Power BI Dataflow imports the table, refreshes the semantic model, and updates the dashboard.&lt;/span&gt;&lt;/div&gt;&lt;/li&gt;
    &lt;/ol&gt;
    &lt;pre id=&quot;payload&quot; class=&quot;card payload&quot; aria-live=&quot;polite&quot;&gt;Select “Prepare Power BI payload” to view the records that the Power BI flow receives.&lt;/pre&gt;
  &lt;/section&gt;
&lt;/div&gt;

&lt;script&gt;
  (function () {
    const root = document.getElementById(&#x27;monthly-data-collection&#x27;);
    const state = {
      records: [
        { team: &#x27;Finance&#x27;, owner: &#x27;Priya Shah&#x27;, email: &#x27;priya.shah@company.com&#x27;, status: &#x27;Submitted&#x27;, submittedAt: &#x27;12 Jul, 09:14&#x27;, actual: 420000, target: 400000, note: &#x27;Forecast locked.&#x27; },
        { team: &#x27;Operations&#x27;, owner: &#x27;Jordan Lee&#x27;, email: &#x27;jordan.lee@company.com&#x27;, status: &#x27;Submitted&#x27;, submittedAt: &#x27;11 Jul, 15:32&#x27;, actual: 93.5, target: 95, note: &#x27;Capacity constrained.&#x27; },
        { team: &#x27;People&#x27;, owner: &#x27;Sam Patel&#x27;, email: &#x27;sam.patel@company.com&#x27;, status: &#x27;Pending&#x27;, submittedAt: &#x27;—&#x27;, actual: null, target: null, note: &#x27;&#x27; },
        { team: &#x27;Commercial&#x27;, owner: &#x27;Mina Chen&#x27;, email: &#x27;mina.chen@company.com&#x27;, status: &#x27;Pending&#x27;, submittedAt: &#x27;—&#x27;, actual: null, target: null, note: &#x27;&#x27; },
        { team: &#x27;Technology&#x27;, owner: &#x27;Chris Gomez&#x27;, email: &#x27;chris.gomez@company.com&#x27;, status: &#x27;Pending&#x27;, submittedAt: &#x27;—&#x27;, actual: null, target: null, note: &#x27;&#x27; }
      ]
    };

    const byId = (id) =&gt; root.querySelector(&#x27;#&#x27; + id);
    const cycle = byId(&#x27;cycle&#x27;);
    const dueDay = byId(&#x27;due-day&#x27;);
    const reminderDays = byId(&#x27;reminder-days&#x27;);
    const trackerBody = byId(&#x27;tracker-body&#x27;);
    const submittedStat = byId(&#x27;submitted-stat&#x27;);
    const outstandingStat = byId(&#x27;outstanding-stat&#x27;);
    const submittedContext = byId(&#x27;submitted-context&#x27;);
    const powerBiStat = byId(&#x27;powerbi-stat&#x27;);
    const powerBiContext = byId(&#x27;powerbi-context&#x27;);
    const deadlineCopy = byId(&#x27;deadline-copy&#x27;);
    const reminderStatus = byId(&#x27;reminder-status&#x27;);
    const formStatus = byId(&#x27;form-status&#x27;);
    const payload = byId(&#x27;payload&#x27;);
    const payloadBadge = byId(&#x27;payload-badge&#x27;);

    function getMonthName() { return cycle.value.split(&#x27; &#x27;)[0]; }
    function updateDeadline() {
      const due = Math.max(1, Math.min(28, Number(dueDay.value) || 18));
      dueDay.value = due;
      deadlineCopy.textContent = cycle.value + &#x27; · submit by &#x27; + due + &#x27; &#x27; + getMonthName() + &#x27;, 17:00&#x27;;
      reminderStatus.textContent = &#x27;Scheduled: email outstanding owners &#x27; + reminderDays.value + &#x27; days before &#x27; + due + &#x27; &#x27; + getMonthName() + &#x27;.&#x27;;
    }

    function renderTracker() {
      const submitted = state.records.filter((record) =&gt; record.status === &#x27;Submitted&#x27;).length;
      const outstanding = state.records.length - submitted;
      submittedStat.textContent = submitted + &#x27; / &#x27; + state.records.length;
      outstandingStat.textContent = String(outstanding);
      submittedContext.textContent = Math.round((submitted / state.records.length) * 100) + &#x27;% complete&#x27;;
      powerBiContext.textContent = state.records.length + &#x27; rows matched to contract&#x27;;
      trackerBody.innerHTML = state.records.map((record) =&gt; {
        const statusClass = record.status === &#x27;Submitted&#x27; ? &#x27;is-complete&#x27; : (record.status === &#x27;Reminder sent&#x27; ? &#x27;is-reminded&#x27; : &#x27;&#x27;);
        return &#x27;&lt;tr&gt;&#x27; +
          &#x27;&lt;td data-label=&quot;Team&quot;&gt;&#x27; + record.team + &#x27;&lt;/td&gt;&#x27; +
          &#x27;&lt;td data-label=&quot;Owner&quot;&gt;&#x27; + record.owner + &#x27;&lt;/td&gt;&#x27; +
          &#x27;&lt;td data-label=&quot;Status&quot;&gt;&lt;span class=&quot;status-mark &#x27; + statusClass + &#x27;&quot;&gt;&#x27; + record.status + &#x27;&lt;/span&gt;&lt;/td&gt;&#x27; +
          &#x27;&lt;td data-label=&quot;Submitted&quot;&gt;&#x27; + record.submittedAt + &#x27;&lt;/td&gt;&#x27; +
          &#x27;&lt;/tr&gt;&#x27;;
      }).join(&#x27;&#x27;);
    }

    function escapeForPayload(value) {
      return String(value || &#x27;&#x27;).replace(/\\/g, &#x27;\\\\&#x27;).replace(/&quot;/g, &#x27;\\&quot;&#x27;).replace(/\n/g, &#x27; &#x27;);
    }

    function makePayload() {
      const records = state.records.map((record) =&gt; ({
        reporting_month: cycle.value,
        team: record.team,
        owner_name: record.owner,
        owner_email: record.email,
        submission_status: record.status,
        submitted_at: record.submittedAt === &#x27;—&#x27; ? null : record.submittedAt,
        actual_value: record.actual,
        target_value: record.target,
        variance: record.actual === null || record.target === null ? null : Number((record.actual - record.target).toFixed(2)),
        comment: record.note
      }));
      return &#x27;[\n&#x27; + records.map((record) =&gt; &#x27;  {&#x27; + Object.entries(record).map(([key, value]) =&gt; &#x27;&quot;&#x27; + key + &#x27;&quot;: &#x27; + (value === null ? &#x27;null&#x27; : (typeof value === &#x27;number&#x27; ? value : &#x27;&quot;&#x27; + escapeForPayload(value) + &#x27;&quot;&#x27;))).join(&#x27;, &#x27;) + &#x27;}&#x27;).join(&#x27;,\n&#x27;) + &#x27;\n]&#x27;;
    }

    byId(&#x27;submission-form&#x27;).addEventListener(&#x27;submit&#x27;, (event) =&gt; {
      event.preventDefault();
      const team = byId(&#x27;team&#x27;).value;
      const owner = byId(&#x27;owner&#x27;).value.trim();
      const email = byId(&#x27;owner-email&#x27;).value.trim();
      const actual = Number(byId(&#x27;metric&#x27;).value);
      const target = Number(byId(&#x27;target&#x27;).value);
      const note = byId(&#x27;note&#x27;).value.trim();
      const timestamp = new Intl.DateTimeFormat(&#x27;en-GB&#x27;, { day: &#x27;2-digit&#x27;, month: &#x27;short&#x27;, hour: &#x27;2-digit&#x27;, minute: &#x27;2-digit&#x27;, hour12: false }).format(new Date()).replace(&#x27;,&#x27;, &#x27;,&#x27;);
      const existing = state.records.find((record) =&gt; record.team === team);
      const update = { team, owner, email, status: &#x27;Submitted&#x27;, submittedAt: timestamp, actual, target, note };
      if (existing) Object.assign(existing, update); else state.records.push(update);
      formStatus.textContent = team + &#x27; submission saved and marked ready for the next Power BI refresh.&#x27;;
      powerBiStat.textContent = &#x27;Ready&#x27;;
      payloadBadge.textContent = &#x27;Data changed · prepare export&#x27;;
      renderTracker();
    });

    byId(&#x27;send-reminders&#x27;).addEventListener(&#x27;click&#x27;, () =&gt; {
      const outstanding = state.records.filter((record) =&gt; record.status !== &#x27;Submitted&#x27;);
      outstanding.forEach((record) =&gt; { record.status = &#x27;Reminder sent&#x27;; });
      const recipients = outstanding.length;
      reminderStatus.textContent = recipients ? &#x27;Reminder queued for &#x27; + recipients + &#x27; outstanding owner&#x27; + (recipients === 1 ? &#x27;.&#x27; : &#x27;s.&#x27;) : &#x27;All owners have completed this collection; no reminders are needed.&#x27;;
      renderTracker();
    });

    byId(&#x27;prepare-payload&#x27;).addEventListener(&#x27;click&#x27;, () =&gt; {
      payload.textContent = makePayload();
      powerBiStat.textContent = &#x27;Prepared&#x27;;
      payloadBadge.textContent = &#x27;Validated payload ready&#x27;;
    });

    cycle.addEventListener(&#x27;change&#x27;, updateDeadline);
    dueDay.addEventListener(&#x27;input&#x27;, updateDeadline);
    reminderDays.addEventListener(&#x27;change&#x27;, updateDeadline);
    updateDeadline();
    renderTracker();
  }());
&lt;/script&gt;

&lt;script src=&quot;https://unpkg.com/@floating-ui/core@1.7.3/dist/floating-ui.core.umd.min.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;https://unpkg.com/@floating-ui/dom@1.7.4/dist/floating-ui.dom.umd.min.js&quot;&gt;&lt;/script&gt;
&lt;script&gt;
(() =&gt; {
  if (window.FloatingUIDOM == null) {
    return;
  }
  const { autoUpdate, computePosition, flip, offset, shift, size } =
    window.FloatingUIDOM;
  const tooltipPlacements = new Set([&quot;top&quot;, &quot;right&quot;, &quot;bottom&quot;, &quot;left&quot;]);
  const tooltipId = `codex-visualization-tooltip-${
    window.crypto?.randomUUID?.() ?? Date.now().toString(36)
  }`;
  const tooltipGap = 5;
  const hoverDelay = 700;
  const skipDelay = 300;
  let activeTrigger = null;
  let pendingTrigger = null;
  let tooltip = null;
  let openTimeout = null;
  let autoUpdateCleanup = null;
  let positionRequest = 0;
  let skipDelayUntil = 0;

  const getTrigger = (target) =&gt;
    target?.nodeType === Node.ELEMENT_NODE
      ? target.closest(&quot;[data-tooltip]&quot;)
      : null;
  const containsTarget = (trigger, target) =&gt;
    target?.nodeType != null &amp;&amp; trigger.contains(target);
  const getContent = (trigger) =&gt;
    trigger.getAttribute(&quot;data-tooltip&quot;)?.trim() ?? &quot;&quot;;
  const getPlacement = (trigger) =&gt; {
    const placement = trigger.getAttribute(&quot;data-tooltip-placement&quot;);
    return tooltipPlacements.has(placement) ? placement : &quot;top&quot;;
  };
  const getTooltip = () =&gt; {
    if (tooltip == null) {
      tooltip = document.createElement(&quot;div&quot;);
      tooltip.id = tooltipId;
      tooltip.className = &quot;tooltip&quot;;
      tooltip.setAttribute(&quot;role&quot;, &quot;tooltip&quot;);
    }
    return tooltip;
  };
  const setDescribedBy = (trigger, described) =&gt; {
    const ids = new Set(
      (trigger.getAttribute(&quot;aria-describedby&quot;) ?? &quot;&quot;)
        .split(/\s+/)
        .filter(Boolean),
    );
    if (described) {
      ids.add(tooltipId);
    } else {
      ids.delete(tooltipId);
    }
    if (ids.size === 0) {
      trigger.removeAttribute(&quot;aria-describedby&quot;);
    } else {
      trigger.setAttribute(&quot;aria-describedby&quot;, [...ids].join(&quot; &quot;));
    }
  };
  const clearOpenTimeout = () =&gt; {
    if (openTimeout != null) {
      window.clearTimeout(openTimeout);
      openTimeout = null;
    }
    pendingTrigger = null;
  };
  const closeTooltip = (activateSkipDelay = true) =&gt; {
    clearOpenTimeout();
    positionRequest += 1;
    autoUpdateCleanup?.();
    autoUpdateCleanup = null;
    if (activeTrigger == null) {
      return;
    }
    setDescribedBy(activeTrigger, false);
    activeTrigger = null;
    tooltip?.remove();
    if (activateSkipDelay) {
      skipDelayUntil = Date.now() + skipDelay;
    }
  };
  const updatePosition = (trigger, floating) =&gt; {
    const request = ++positionRequest;
    void computePosition(trigger, floating, {
      middleware: [
        offset(tooltipGap),
        flip({ padding: tooltipGap }),
        shift({ padding: tooltipGap }),
        size({
          padding: tooltipGap,
          apply({ availableHeight, availableWidth, elements }) {
            elements.floating.style.setProperty(
              &quot;--tooltip-available-width&quot;,
              `${Math.max(0, availableWidth)}px`,
            );
            elements.floating.style.setProperty(
              &quot;--tooltip-available-height&quot;,
              `${Math.max(0, availableHeight)}px`,
            );
          },
        }),
      ],
      placement: getPlacement(trigger),
      strategy: &quot;fixed&quot;,
    })
      .then(({ x, y }) =&gt; {
        if (activeTrigger !== trigger || request !== positionRequest) {
          return;
        }
        const scale = window.devicePixelRatio || 1;
        floating.style.transform = `translate(${Math.round(x * scale) / scale}px, ${Math.round(y * scale) / scale}px)`;
        floating.style.visibility = &quot;visible&quot;;
      })
      .catch(() =&gt; {
        if (activeTrigger === trigger &amp;&amp; request === positionRequest) {
          closeTooltip(false);
        }
      });
  };
  const openTooltip = (trigger) =&gt; {
    const content = getContent(trigger);
    if (!trigger.isConnected || content.length === 0) {
      return;
    }
    clearOpenTimeout();
    if (activeTrigger === trigger) {
      return;
    }
    closeTooltip();
    const floating = getTooltip();
    floating.textContent = content;
    floating.style.visibility = &quot;hidden&quot;;
    floating.style.transform = &quot;translate(0, 0)&quot;;
    document.body.appendChild(floating);
    activeTrigger = trigger;
    setDescribedBy(trigger, true);
    autoUpdateCleanup = autoUpdate(trigger, floating, () =&gt; {
      updatePosition(trigger, floating);
    });
  };
  const requestOpen = (trigger, immediate = false) =&gt; {
    if (
      getContent(trigger).length === 0 ||
      activeTrigger === trigger ||
      pendingTrigger === trigger
    ) {
      return;
    }
    clearOpenTimeout();
    pendingTrigger = trigger;
    const delay =
      immediate || activeTrigger != null || Date.now() &lt; skipDelayUntil
        ? 0
        : hoverDelay;
    if (delay === 0) {
      openTooltip(trigger);
      return;
    }
    openTimeout = window.setTimeout(() =&gt; {
      openTimeout = null;
      pendingTrigger = null;
      openTooltip(trigger);
    }, delay);
  };
  const handlePointerOpen = (event) =&gt; {
    if (event.pointerType === &quot;touch&quot;) {
      return;
    }
    const trigger = getTrigger(event.target);
    if (trigger == null || containsTarget(trigger, event.relatedTarget)) {
      return;
    }
    requestOpen(trigger);
  };
  const handleLeave = (event) =&gt; {
    const trigger = getTrigger(event.target);
    if (trigger == null || containsTarget(trigger, event.relatedTarget)) {
      return;
    }
    if (activeTrigger === trigger || pendingTrigger === trigger) {
      closeTooltip();
    }
  };
  const handleFocusIn = (event) =&gt; {
    const trigger = getTrigger(event.target);
    if (trigger?.matches(&quot;:focus-visible&quot;)) {
      requestOpen(trigger, true);
    }
  };
  const handleKeyDown = (event) =&gt; {
    if (event.key === &quot;Escape&quot;) {
      closeTooltip();
    }
  };
  const handleContextMenu = (event) =&gt; {
    const trigger = getTrigger(event.target);
    if (activeTrigger === trigger || pendingTrigger === trigger) {
      closeTooltip();
    }
  };
  const destroy = () =&gt; {
    closeTooltip(false);
    document.removeEventListener(&quot;pointerover&quot;, handlePointerOpen);
    document.removeEventListener(&quot;pointerout&quot;, handleLeave);
    document.removeEventListener(&quot;focusin&quot;, handleFocusIn);
    document.removeEventListener(&quot;focusout&quot;, handleLeave);
    document.removeEventListener(&quot;keydown&quot;, handleKeyDown);
    document.removeEventListener(&quot;contextmenu&quot;, handleContextMenu);
    tooltip = null;
  };

  document.addEventListener(&quot;pointerover&quot;, handlePointerOpen);
  document.addEventListener(&quot;pointerout&quot;, handleLeave);
  document.addEventListener(&quot;focusin&quot;, handleFocusIn);
  document.addEventListener(&quot;focusout&quot;, handleLeave);
  document.addEventListener(&quot;keydown&quot;, handleKeyDown);
  document.addEventListener(&quot;contextmenu&quot;, handleContextMenu);
  window.addEventListener(&quot;pagehide&quot;, destroy, { once: true });
})();
&lt;/script&gt;
&lt;script id=&quot;codex-visualization-lucide&quot; async src=&quot;https://unpkg.com/lucide@1.17.0/dist/umd/lucide.js&quot;&gt;&lt;/script&gt;
&lt;script&gt;
(() =&gt; {
  const initialize = () =&gt; {
    globalThis.lucide?.createIcons({ attrs: { width: 16, height: 16 } });
  };
  if (globalThis.lucide != null) {
    initialize();
    return;
  }
  document
    .getElementById(&quot;codex-visualization-lucide&quot;)
    ?.addEventListener(&quot;load&quot;, initialize, { once: true });
})();
&lt;/script&gt;

&lt;/body&gt;
&lt;/html&gt;
"></iframe>
</body>
</html>
