// Обработка отправки формы
document.getElementById('contactForm').addEventListener('submit', function (e) {
  e.preventDefault();

  const name = document.getElementById('name').value;
  const email = document.getElementById('email').value;
  const message = document.getElementById('message').value;

  if (name && email && message) {
    alert('Сообщение успешно отправлено!');
    this.reset();
  } else {
    alert('Пожалуйста, заполните все поля.');
  }
});
