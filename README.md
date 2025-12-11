<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Farmers Village Hub</title>
  <style>
    body { margin:0; font-family: "Segoe UI", sans-serif; background:#eef2e6; }
    header {
      background: linear-gradient(135deg, #2e7d32, #66bb6a);
      padding: 40px 20px;
      color:white;
      text-align:center;
      box-shadow:0 4px 10px rgba(0,0,0,0.2);
    }
    header h1 { font-size: 2.6rem; margin:0; }

    nav {
      display:flex;
      justify-content:center;
      gap:20px;
      padding:15px;
      background:white;
      box-shadow:0 4px 10px rgba(0,0,0,0.1);
      position:sticky;
      top:0;
      z-index:10;
    }
    nav a {
      text-decoration:none;
      padding:10px 18px;
      border-radius:8px;
      background:#4caf50;
      color:white;
      font-weight:600;
      transition:0.3s;
    }
    nav a:hover { background:#2e7d32; }

    .page {
      display:none;
      padding:20px;
      max-width:1000px;
      margin:20px auto;
      background:white;
      border-radius:10px;
      box-shadow:0 4px 12px rgba(0,0,0,0.1);
    }
    .active { display:block; }

    table {
      width:100%; border-collapse:collapse; margin-top:10px;
      background:white;
      border-radius:10px;
      overflow:hidden;
      box-shadow:0 3px 10px rgba(0,0,0,0.1);
    }
    th {
      backg
