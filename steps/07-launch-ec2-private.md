# Step 7 — Launch EC2 in Private Subnet

**Goal:** Launch a private instance without public IP.**

**Steps:**
1. Go to **EC2** → click **Launch instance**.
2. Configure:
   - Name: `private-ec2`
   - Network: `my-vpc`
   - Subnet: `private-subnet-1`
   - Auto-assign Public IP: `Disable`
   - Security group: `sg-private`
3. Launch.

✅ Private EC2 instance is running but cannot be accessed directly.
