# dreams-luxury
dreams-luxury
<!DOCTYPE html><html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dreams Luxury</title>
  <style>
    body { font-family: sans-serif; margin: 0; padding: 0; background: #f4f4f4; }
    .container { max-width: 800px; margin: auto; padding: 20px; background: #fff; }
    h1, h2 { color: #2c3e50; }
    .product img { max-width: 100%; height: auto; }
    form { margin-top: 20px; }
    input, textarea { width: 100%; padding: 10px; margin: 10px 0; }
    button { padding: 10px 20px; background: #27ae60; color: white; border: none; cursor: pointer; }
    button:hover { background: #219150; }
  </style>
  <script>
    function sendEmail(e) {
      e.preventDefault();
      const name = document.getElementById('name').value;
      const phone = document.getElementById('phone').value;
      const address = document.getElementById('address').value;
      const mailtoLink = `mailto:alismailsohan@gmail.com?subject=New Order from ${name}&body=Name: ${name}%0APhone: ${phone}%0AAddress: ${address}`;
      window.location.href = mailtoLink;
    }
  </script>
</head>
<body>
  <div class="container">
    <h1>Dreams Luxury</h1>
    <p>Dreams Luxury হল একটি প্রিমিয়াম অনলাইন শপ যেখানে আপনি স্টাইলিশ ও আধুনিক পণ্য পাবেন। আমরা মান, আস্থা ও গ্রাহক সন্তুষ্টিকে সর্বোচ্চ গুরুত্ব দিয়ে থাকি।</p><h2>আমাদের পণ্য</h2>
<div class="product">
  <img src="https://via.placeholder.com/600x400" alt="ডেমো পণ্য">
  <h3>স্টাইলিশ হ্যান্ডব্যাগ</h3>
  <p>উচ্চমানের লেদার দিয়ে তৈরি, দৈনন্দিন ব্যবহারের জন্য উপযুক্ত। ট্রেন্ডি ডিজাইন ও মজবুত কোয়ালিটি।</p>
</div>

<h2>অর্ডার করুন</h2>
<form onsubmit="sendEmail(event)">
  <label for="name">নাম:</label>
  <input type="text" id="name" name="name" required>

  <label for="phone">ফোন নম্বর:</label>
  <input type="tel" id="phone" name="phone" required>

  <label for="address">ঠিকানা:</label>
  <textarea id="address" name="address" rows="3" required></textarea>

  <button type="submit">অর্ডার করুন</button>
</form>

  </div>  <!-- লাইভ চ্যাট (Tawk.to demo) -->  <script type="text/javascript">
  var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
  (function(){
  var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
  s1.async=true;
  s1.src='https://embed.tawk.to/64ac28d7cc26a871b0274891/1h5k6cdnc'; // এটা আপনি আপনার একাউন্ট দিয়ে পরিবর্তন করতে পারবেন
  s1.charset='UTF-8';
  s1.setAttribute('crossorigin','*');
  s0.parentNode.insertBefore(s1,s0);
  })();
  </script></body>
</html>
