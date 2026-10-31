# Window Peeper AI: task status and recovery

What happens between choosing a photo and downloading an MP4 on [Window Peeper AI](https://windowpeeperai.pro/), and what to do when something stalls. Based on the [guide](https://windowpeeperai.pro/guide) (updated 2026-10-23), checked 2026-10-31.

## The flow

| Stage | What is true at this point |
|---|---|
| Photo selected | The file is still only on your device |
| Signed in | The browser tries to keep your photo draft; if not, choose it again |
| Credits bought | A return from checkout is not payment confirmation; the server updates the balance. Buying never starts a video |
| Make my Window Peeper video | A task is created: 10 credits for 480p, 20 for 720p |
| Waiting | You can leave the page. Open **My videos**; refreshing finds the saved task, it does not start a new one |
| Ready | Only after the result is saved and its output spec is checked. Then **Download MP4** |

The recorded model run took 417 seconds. That is one observation, not a promised turnaround.

## When something goes wrong

| Situation | Do | Don't |
|---|---|---|
| Checkout redirect is slow | Wait for the balance to update | Buy again |
| Photo rejected locally | Fix format, size (≤10 MB) or dimensions (short side ≥512 px) | Retry the same file |
| Supplier rejects an accepted upload | Read the recorded failure and returned allowance | Assume credits are lost |
| Task shows "Needs review" or unknown | Contact support with the task ID | Resubmit or pay again |
| Confirmed technical failure | Check task and balance; credits are returned once | Treat it as a cash refund |
| Playback or download fails | Reload access to the existing result | Generate a new video |
| Face, hands or ending look wrong | Keep the task ID, describe it to support | Expect a re-run to fix it |

A returned allowance is not a cash refund; billing is separate (see [pricing](https://windowpeeperai.pro/pricing)).

See also [editorial-method.md](editorial-method.md) and [related-search-labels.md](related-search-labels.md).

Maintained by Chaozi, operator of windowpeeperai.pro.
