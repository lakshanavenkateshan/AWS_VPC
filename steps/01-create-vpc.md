# Step 1 — Create VPC

**Goal:** Create a VPC with CIDR block `10.0.0.0/16`.

**Web UI steps (GitHub-style writeup for AWS Console):**
1. Open AWS Console → VPC service.
2. Click **Create VPC**.
3. Choose:
   - Name tag: `my-vpc`
   - IPv4 CIDR block: `10.0.0.0/16`
   - Tenancy: Default
4. Click **Create VPC**.

**Checklist**
- [ ] VPC created with correct CIDR
- [ ] Note the VPC ID for later steps
