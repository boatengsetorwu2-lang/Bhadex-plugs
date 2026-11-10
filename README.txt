BHADEX PLUGS - Netlify + Paystack setup

1. Deploy this folder to Netlify (or upload the ZIP through Netlify Drop).
2. In Netlify Site configuration > Environment variables, add:
   PAYSTACK_SECRET_KEY = your Paystack TEST secret key (starts sk_test_)
3. Redeploy after adding the variable.
4. Test only using Paystack test keys and test payment details.
5. Before live payments, a responsible adult/account owner should verify Paystack account eligibility, ownership, business compliance, live keys, delivery/refund policies, and end-to-end verification.
Never put the secret key in index.html or send it in chat.
Public key is not required for this server-initialized redirect checkout flow.
