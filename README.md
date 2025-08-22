# style-css
* { box-sizing: border-box; }
body {
  margin: 0;
  font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
  background: #0b1220;
  color: #e6ebf5;
}
.app {
  max-width: 720px;
  margin: 40px auto;
  padding: 0 16px;
}
h1 {
  font-size: 28px;
  margin-bottom: 16px;
  text-align: center;
}
.card {
  background: #111a2e;
  border: 1px solid #1b2742;
  border-radius: 16px;
  padding: 16px;
  margin: 16px 0;
  box-shadow: 0 4px 24px rgba(0,0,0,0.2);
}
button {
  padding: 10px 16px;
  border: none;
  border-radius: 10px;
  background: #3a68ff;
  color: white;
  cursor: pointer;
  font-weight: 600;
}
button:hover { opacity: .95; }
button:disabled { opacity: .5; cursor: not-allowed; }
.status { margin-top: 8px; }
.network { margin-top: 4px; opacity: .8; }
.small { font-size: 12px; opacity: .8; margin-top: 8px; }
pre {
  white-space: pre-wrap;
  word-break: break-word;
  background: #0a101f;
  padding: 12px;
  border-radius: 10px;
  min-height: 36px;
}
input {
  width: 100%;
  padding: 10px 12px;
  margin: 8px 0 12px;
  border-radius: 10px;
  border: 1px solid #253250;
  background: #0a101f;
  color: #e6ebf5;
}
footer { text-align: center; margin: 24px 0; opacity: .7; }
