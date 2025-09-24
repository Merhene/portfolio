# Custom Domain Setup Guide for merhene.com

## DNS Configuration Required

Add these A records in your domain registrar's DNS settings:

### Record 1 (Root domain)
- **Type**: A
- **Name**: @ (or merhene.com)
- **Value**: 76.76.21.21
- **TTL**: 300 or Auto

### Record 2 (WWW subdomain)
- **Type**: A
- **Name**: www
- **Value**: 76.76.21.21
- **TTL**: 300 or Auto

## Registrar-Specific Instructions

### Cloudflare
1. Dashboard → DNS → Records
2. Add Record → Type: A, Name: @, IPv4: 76.76.21.21, Proxied: ON
3. Add Record → Type: A, Name: www, IPv4: 76.76.21.21, Proxied: ON

### Namecheap
1. Domain List → Manage → Advanced DNS
2. Add New Record → A Record, Host: @, Value: 76.76.21.21
3. Add New Record → A Record, Host: www, Value: 76.76.21.21

### Google Domains
1. DNS → Custom resource records
2. Add → Name: @, Type: A, Data: 76.76.21.21
3. Add → Name: www, Type: A, Data: 76.76.21.21

## Verification Commands

Check DNS propagation:
```bash
npx vercel domains ls
```

Check domain status:
```bash
nslookup merhene.com
nslookup www.merhene.com
```

## Timeline
- DNS propagation: 15 minutes - 48 hours (usually 30 minutes)
- SSL certificate: Automatic once DNS is verified
- Your site will be live at: https://www.merhene.com

## Cost
- Domain: ~$10-15/year
- Hosting: FREE (Vercel)
- SSL: FREE (Vercel)
- Total: ~$10-15/year
