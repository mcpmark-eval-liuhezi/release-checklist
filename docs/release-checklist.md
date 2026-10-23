# Release Checklist v3 (DRAFT)

Prepared for the quarterly release train.
Proposed by the platform team.

## Steps

1. **Freeze the release branch and open the change freeze.**
2. **Snapshot the primary database.**
3. **Purge the edge cache immediately after the deploy finishes.**
4. **Drain the connection pool (allow up to 30 minutes).**
5. **Rotate the gateway tokens.**
6. **Verify canary metrics for 20 minutes before full rollout.**
7. **Publish the release notes.**
8. **Close the change freeze and unfreeze the branch.**
