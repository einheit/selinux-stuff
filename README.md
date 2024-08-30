fix-selinux-alerts.pl is a script which attempts to automatically remdiate selinux alerts by adding custom policies.
It's not neccesarily optimal, elegant or correct, but it's meant to be a quick and easy way to create exceptions for any sort of cool ways you might want to color outside the lines.

The pattern matching heuristics are not neccesarily robust, and could break with new versions of any of the software on which it depends.

Written, tested and successfully uised on RHEL 9. It should work on any equivalent distros.
