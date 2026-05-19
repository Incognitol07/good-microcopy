# good-microcopy

A skill for AI agents that ensures every piece of UI text is intentional, clear, and human. Automatically, without being asked.

```bash
npx skills add incognitol07/good-microcopy
```

---

## What it does

Most AI-generated UIs have technically correct copy that feels like it was written by a machine. Button labels say "Submit". Errors say "Something went wrong". Empty states are blank. Loading screens show spinners with no context.

This skill fixes that. It applies 10 microcopy principles drawn from [goodmicrocopy.com](https://goodmicrocopy.com), a curated collection of real UI copy from Slack, Apple, Uber, YouTube, Buffer, and 100+ other products, so your agent writes UI text the way a senior UX writer would.

It activates automatically whenever your agent is building any user-facing screen or flow. You don't have to ask for it.

---

## The 10 principles

1. **Set expectations**: tell users what will happen before they wonder
2. **Provide context at the right moment**: not front-loaded, not buried
3. **Give specific feedback**: "Your card ending in 4242 was updated" not "Saved"
4. **Speak the user's language**: outcome-based labels, first-person choices, no jargon
5. **Don't blame users for errors**: own it, then point forward
6. **Reassure at anxiety points**: email fields, payment, permissions, trials
7. **Guide without controlling**: suggest the good path, preserve autonomy
8. **Treat empty states as product moments**: invitations, not dead ends
9. **Use personality, but clarity wins**: brand voice never obscures meaning
10. **Sweat the small stuff**: every word a user reads is an interaction

---

## Example output

**Prompt:** Write the copy for a student thriftwear marketplace

**Without this skill:**

> - Button: `Submit`
> - Error: `Something went wrong`
> - Empty cart: `Your cart is empty`
> - After payment: `Order placed`

**With this skill:**

> - Button: `Start buying` / `List this item`
> - Error: `Your payment didn't go through. Double-check the card details or try a different one. Your cart is still saved.`
> - Empty cart: `Your cart is empty. Your next favourite piece is out there. Go find it.`
> - After payment: `Order placed. {{seller_name}} has 3 days to ship and will send you tracking. You're protected if anything goes wrong.`

---

## Works with

Claude Code, Cursor, Windsurf, Cline, and any agent that supports the skills format.

---

## Based on

All principles are synthesized from [goodmicrocopy.com](https://goodmicrocopy.com) by [@richardsison](https://twitter.com/richardsison), a curated collection of real-world microcopy examples from products that do it right.
