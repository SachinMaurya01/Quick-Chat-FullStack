# Googlr auth login

<!-- https://console.cloud.google.com/auth/clients?highlightClient=540225333944-1s7q0b6rk3gc7dn5l9j88iqt6l0nicgh.apps.googleusercontent.com&project=quick-chat-451111 -->
1. Add the live url to google console inside Authorised JavaScript origins ( OAuth Client )
2. Add this one also in redirect url for production

    For production: https://{YOUR_DOMAIN}/api/auth/callback/google

# To create migration in Prisma 
    npx prisma migrate dev --name=user_table 