using formsubmit for mails

```html
<form action="https://formsubmit.co/your-email@example.com" method="POST">
    <label>Name:</label>
    <input type="text" name="name" required>

    <label>Email:</label>
    <input type="email" name="email" required>

    <label>Message:</label>
    <textarea name="message" required></textarea>

    <button type="submit">Send Message</button>
</form>
```