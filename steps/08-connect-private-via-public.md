# Step 8 — Connect to Private Instance via Public Instance

**Goal:** Access private EC2 using public EC2 as a jump server.**

**Steps:**
1. First connect to **public-ec2** via RDP/SSH using its public IP.
2. From the public machine, use:
   - RDP/SSH client
   - Copy private EC2’s internal IP
   - Connect using private key (.pem)
3. Now you are inside private instance via the bastion host.

✅ You can manage the private instance safely.
