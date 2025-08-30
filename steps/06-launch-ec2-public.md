# Step 6 — Launch EC2 in Public Subnet

**Goal:** Launch a public instance to act as a bastion host (jump server).**

**Steps:**
1. Go to **EC2** → click **Launch instance**.
2. Configure:
   - Name: `public-ec2`
   - Network: `my-vpc`
   - Subnet: `public-subnet-1`
   - Auto-assign Public IP: `Enable`
   - Security group: `sg-public`
3. Add key pair (.pem file) for RDP/SSH access.
4. Launch.

✅ Public EC2 instance is running with public IP.
