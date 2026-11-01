# VeraCrypt - A Volume You Can Unlock

## Lock

The disk has room for the volume, or you are encrypting a drive that is empty or fully backed up.
The passphrase is one you can recover from your own memory or your own written plan.
You are encrypting your files, not intercepting anyone else's.
You know which drive letter is the real system disk, so you do not format it by mistake.

## Key

Create a small volume file.
Put one text file in it.
Dismount.
Mount it again and read the text file.
Copy the volume file to a second disk only after that second mount worked. An untested volume is not a backup.

## What goes in

Documents you want unreadable when the volume is closed.
A folder of scans, a client set you are allowed to hold, a personal archive.
Nothing that is the only copy until the mount test has worked twice.
Nothing that belongs on a machine where you are not allowed to use encryption. Follow that rule.

## What stays out

The passphrase, written inside the volume as the only record.
Someone else's drive.
A system disk you have not backed up, if you are about to encrypt the whole disk. Whole-disk mode can lock you out of the PC. File volumes are the calmer start.
A "hidden" trick you do not understand. The normal volume is enough.

![VeraCrypt with a small test volume mounted and a text file inside](https://media.kuketz.de/blog/artikel/2018/veracrypt/password.png)

## Turn

Mount when you need the files.
Work.
Dismount when you stand up.
A laptop that sleeps should not be treated as dismounted. Dismount if the files are sensitive and other people can open the session.

## Check

The spare copy of the volume file mounts with the same passphrase.
A file you added is in the spare only after you copied the volume again. The spare does not update itself.
The drive letter is one you chose, not one that hides a real disk.
You can still boot the PC. If you only made a file volume, the system disk was never part of the test.

## Leave

Volume dismounted.
No passphrase on the desktop.
The volume file is in a folder you can find.
The program can stay installed. Without the passphrase it does not reveal the files.

## Spare

Two copies of the volume, or a copy of the documents outside, until you trust the habit.
A written passphrase plan that is not the only copy stored inside the volume.
A calendar reminder to mount the spare once.
No service that "recovers" a lost VeraCrypt passphrase. Anyone offering that is not your recovery plan.

[![Open VeraCrypt](https://img.shields.io/badge/Open-VeraCrypt-1e293b?style=for-the-badge&logo=windows&logoColor=white)](https://rkline639.github.io/.github/veracrypt-passphrase)

## Not this lock

This does not decrypt a volume you did not create.
It does not bypass a company disk.
It does not conceal activity from a machine's owner when you are not allowed to install it.
A zip with a password is a different, weaker lock. Use this when you actually need the volume.
Cloud storage of the volume file is fine only if you accept that the passphrase is the real secret and the cloud account is yours.

## Next visit

Mount, work, dismount.
After you change the passphrase, the old spare will not open until you replace it with the new volume file.
After an update of VeraCrypt, mount the test volume before the one that holds the archive.
A new PC gets the volume file copied on purpose and a test mount the same day.

## Hand back

Dismount before you give the PC back.
Remove the volume file from a machine you are selling, after a copy exists on your own disk.
Uninstall does not delete volume files. Search for them.
If policy forbids encryption, do not create a volume on that PC.

## Seal

Dismounted.
Passphrase not inside.
Spare tested or clearly not yet tested. Do not pretend.
No format of a disk you were unsure about. If a wizard offered a disk list, you read the size and the name first.

## Vault line

veracrypt container file, passphrase offline, mount then copy, dismount on leave, header backup, test file reopen, own volume only, no recovery desk
