cd "/c/Users/Admin/WorkBuddy AI/2026-10-10-23-38-02/Guskolx"

# profile README
git clone https://github.com/Guskolx/Guskolx.git _profile
cp README.md _profile/README.md
cd _profile && git add . && git commit -m "Add profile README" && git push && cd ..

# VISION-FLOW README
git clone https://github.com/Guskolx/VISION-FLOW.git _visionflow
cp VISION-FLOW-README.md _visionflow/README.md
cd _visionflow && git add . && git commit -m "docs: rewrite README with overview, architecture and API reference" && git push
