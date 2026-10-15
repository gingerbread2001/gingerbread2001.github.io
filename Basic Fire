<header>
  <h1>Capital Fire & Rescue Service</h1>
  <p>Basic Firefighter Guide</p>
</header>

<section id="mdt">
  <h2>Using the Fire MDT</h2>
  <ol>
    <li>Open the MDT.</li>
    <li>Select General Firefighting.</li>
    <li>Choose an available assignment.</li>
    <li>Book on and verify your status.</li>
  </ol>
</section>
body {
  font-family: Arial, sans-serif;
  background: #f4f7fb;
  color: #1e293b;
  margin: 0;
}

header {
  background: #101d32;
  color: white;
  padding: 40px;
  border-bottom: 4px solid #d92f3d;
}

h2 {
  color: #101d32;
}
const checklist = document.querySelectorAll(
  '#checklist input[type="checkbox"]'
);

checklist.forEach(item => {
  item.addEventListener('change', () => {
    const checked = [...checklist]
      .filter(box => box.checked).length;

    console.log(`${checked} items checked`);
  });
});
