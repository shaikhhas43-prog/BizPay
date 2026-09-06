# BizPay Complete Prototype

Files:
- index.html — mobile-first BizPay user app
- BizPay_Admin.html — admin dashboard

## Supabase
Both files use the existing BizPay Supabase project URL, but intentionally leave the publishable key as a placeholder.

Replace:
PASTE_YOUR_SUPABASE_PUBLISHABLE_KEY_HERE

Use ONLY the Supabase publishable/anon key. Never put a service_role/secret key in GitHub.

## Existing SQL functions expected by admin
- bizpay_admin_list_kyc()
- bizpay_admin_review_kyc(p_user_id uuid, p_status text)
- bizpay_admin_list_redeems()
- bizpay_admin_review_redeem(p_request_id uuid, p_status text)

## Important
This is a prototype. KYC is not official KYC, and redeem approval does not send real money. Do not enter real PAN/Aadhaar/bank credentials into this demo.
