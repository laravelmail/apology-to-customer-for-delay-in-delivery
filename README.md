# Apology To Customer For Delay In Delivery

Professional apology template for logistics companies to use when there is a delay in delivery.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Logistics
- **Message Type:** Transactional
- **Tags:** delivery, apology, delay

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/apology-to-customer-for-delay-in-delivery.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/apology-to-customer-for-delay-in-delivery/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.apology-to-customer-for-delay-in-delivery',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
