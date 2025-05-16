# 🧾 TransactionPay PrestaShop Module

**The Official PrestaShop Plugin for TransactionPay**  
Accept secure online payments from your customers using TransactionPay on your PrestaShop store.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![PrestaShop](https://img.shields.io/badge/PrestaShop-1.7%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 📦 Features

- Accept payments via TransactionPay
- Secure redirection or inline checkout
- Test and Live mode support
- Real-time order status updates via webhooks
- Simple and intuitive configuration interface

---

## ⚙️ Installation

### Manual Installation

1. **Download the Plugin**
   - Get the latest release from the [Releases](#) section or clone this repo.

2. **Upload to PrestaShop**
   - Go to your PrestaShop Admin Panel.
   - Navigate to `Modules > Module Manager > Upload a Module`.
   - Upload the `.zip` file or folder.

3. **Install the Module**
   - After upload, PrestaShop will prompt you to install. Click **Install**.
   - You’ll see a success message once the module is successfully installed.

---

## 🔧 Configuration

1. Go to `Modules > Module Manager > TransactionPay > Configure`.
2. Enter your TransactionPay credentials:
   - **Public API Key**
   - **Secret API Key**
   - **Environment**: `Test` or `Live`
3. Save your configuration.

---

## 🔁 Webhook Setup

To ensure order statuses are updated correctly:

1. Copy the **Webhook URL** from the module's configuration screen.
2. Login to your [TransactionPay Dashboard](#).
3. Navigate to **Settings > Webhooks**.
4. Add a new webhook using the URL and enable events like:
   - `payment.success`
   - `payment.failed`

---

## 💳 Customer Payment Flow

1. Customer chooses TransactionPay during checkout.
2. They are redirected to a secure payment page (or pay inline).
3. Upon completion, they return to your site.
4. Order status is updated based on webhook confirmation.

---

## 🧪 Testing

- Enable **Test Mode** in module settings.
- Use TransactionPay test card credentials.
- Place a test order and confirm the flow.

---

## 🛠️ Troubleshooting

| Issue | Solution |
|-------|----------|
| Payment option not visible | Ensure the module is enabled and supports the selected currency and shipping zone |
| Invalid API credentials | Double-check your Public and Secret keys from TransactionPay |
| Webhook not working | Ensure the URL is publicly accessible and configured properly in TransactionPay Dashboard |

---

## 📚 Resources

- [TransactionPay Documentation](#)
- [Report an Issue](#)
- [Support](#)

---

## 📝 License

This module is open-sourced under the [MIT License](LICENSE).

---

## 🙌 Contributing

PRs and suggestions are welcome! Please open an issue or submit a pull request.

---

## 🧑‍💻 Maintainers

Built and maintained by the TransactionPay team.

---

