# review-workflows
Shared GitHub Actions workflows for AI PR review (PRAgent + CodeRabbit fallback)

## Using it in a repo

Copy [`stub/.github/workflows/ai-review.yml`](stub/.github/workflows/ai-review.yml) into the repo unchanged and add one Actions secret, `MINIMAX_API_KEY`. The stub pins this workflow to a reviewed commit SHA; bump that SHA deliberately after reviewing changes here.
