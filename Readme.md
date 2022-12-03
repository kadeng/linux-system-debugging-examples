
## Notes

### How to determine available variables within a systap probe:

Use "-L" - Example:

```bash
stap -L 'kernel.function("do_send_sig_info")'
```