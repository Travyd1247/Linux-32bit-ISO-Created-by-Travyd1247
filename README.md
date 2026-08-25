# MyLinux i386 GitHub Actions build

Upload the `.github/workflows/build-iso.yml` file to your repository.

Then open GitHub **Actions → Build MyLinux i386 ISO → Run workflow**.

The runner installs the required tools, downloads Linux 7.2 and BusyBox,
builds a 32-bit i386 kernel, creates the root filesystem and GRUB BIOS ISO,
checks the ISO is below 500 MB, and uploads `mylinux-i386.iso` as an artifact.
