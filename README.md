# FeroXOs

FeroXOs is a lightweight custom Linux-based operating system project.

It includes bootable ISO images and a VirtualBox OVA appliance so the OS can be tested, installed, and developed easily.

## Downloads

The repository includes:

- `images/feroxos.iso` - bootable ISO image
- `images/FeroOS2.ova` - VirtualBox appliance

Large image files are tracked with Git LFS.

## Running in VirtualBox

### Option 1: Import the OVA

1. Open VirtualBox.
2. Go to `File > Import Appliance`.
3. Select `images/FeroOS2.ova`.
4. Import and start the VM.

### Option 2: Boot the ISO

1. Create a new VirtualBox VM.
2. Choose Linux as the OS type.
3. Attach `images/feroxos.iso` as the optical disk.
4. Start the VM.

## Project Structure

```text
crates/      Rust source code
docs/        Documentation
images/      ISO and OVA builds
scripts/     Build/helper scripts
tools/       Development tools
