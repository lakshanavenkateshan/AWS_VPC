# Step 5 — Create Security Groups

**Goal:** Control inbound/outbound traffic for EC2 instances.**

**Steps:**
1. Go to **Security Groups** → click **Create security group**.
2. For **Public EC2**:
   - Name: `sg-public`
   - Inbound rules: allow RDP (3389), HTTP (80), HTTPS (443), SSH (22)
   - Source: `0.0.0.0/0`
3. For **Private EC2**:
   - Name: `sg-private`
   - Inbound rules: allow only traffic from `sg-public`
   - This ensures private machine is accessible only through public machine.

✅ Security groups are ready.
