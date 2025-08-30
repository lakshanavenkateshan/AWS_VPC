# Step 2 — Create subnets (public & private)

**Goal:** Create public and private subnets across AZs.

**Web UI steps:**
1. AWS Console → VPC → Subnets → **Create subnet**.
2. Choose VPC: `my-vpc`.
3. For public subnet:
   - Name: `public-subnet-1`
   - CIDR: `10.0.1.0/24`
   - AZ: choose one
4. For private subnet:
   - Name: `private-subnet-1`
   - CIDR: `10.0.2.0/24`
5. Create more subnets (AZ redundancy) by repeating.

**Tip:** Prefix names with `public-`/`private-` and order them `01-`, `02-`.
