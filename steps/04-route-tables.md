# Step 4 — Configure Route Tables

**Goal:** Route traffic properly for public and private subnets.**

**Steps:**
1. Go to **Route Tables** → click **Create route table**.
2. Name: `public-rt`, select VPC: `my-vpc`.
3. Edit routes:
   - Destination: `0.0.0.0/0`
   - Target: Internet Gateway (`my-igw`)
4. Associate `public-subnet-1` with `public-rt`.

For private subnet:
1. Create another route table → Name: `private-rt`.
2. Associate `private-subnet-1` with `private-rt`.
3. Do **not** add internet route here (private has no direct internet).

✅ Public subnet can reach the internet, private subnet cannot.
