
# mod01_intro_ex01_get_aboard
The purpose of this exercise is to introduce you to the CDP Cluster. You will log in to the cluster and take a tour of the remote desktop. You will be shown how to copy and paste from your desktop into the remote desktop.

1 Your instructor will provide you an IP address, a login, and a password. Please write these down where you will have ready access. Enter the IP address into your browser. Log in to your cluster.
![Your instructor will provide you an IP address, a login, and a password. Please write these down where you will have ready access. Enter the IP address into your browser. Log in to your cluster.](steps-mod01_intro_ex01_get_aboard1/yICxe5.png)
Cloudera Educational Services recommends either Chrome or Firefox for a browser.

The connection service is Apache Guacamole. After a long idle period, the Guacamole client will time out by design. You will be prompted to Reconnect. If this does not reconnect click refresh on the IP address. If there is still an issue request assistance.

Warning: The most common reason for connectivity issues is accessing the cluster through a VPN. Check the status of your connection. If you are connecting through a VPN you should drop this connection.

2 Copy and paste from Pluma into a Mate Terminal.  Use both menu and keyboard copy and paste commands.
![Copy and paste from Pluma into a Mate Terminal.  Use both menu and keyboard copy and paste commands.](steps-mod01_intro_ex01_get_aboard1/step_1.png)
- Menu: Edit > Copy and Edit > Paste
- Keyboard: Ctlr+C and Shift+Ctlr+V

The Mate Terminal requires the use of the Shift key when using keyboard copy and paste. Practice this routine several times.

3 The only password used in this cluster is "BadPass@1". This is the password for all users, databases, and configurations. Please write it down. Keep it visible throughout the course. In the course material wherever you see <password> enter this password.

4 You will log into a Mate remote desktop. The Firefox, Mate Terminal, and Pluma icons are located on the top bar. There are two workspaces on the bottom bar.
![You will log into a Mate remote desktop. The Firefox, Mate Terminal, and Pluma icons are located on the top bar. There are two workspaces on the bottom bar.](steps-mod01_intro_ex01_get_aboard1/step_3.png)

## 5 Guacamole has a side panel for communicating with the remote desktop. One feature is the clipboard. Open the Guacamole side panel.
![Guacamole has a side panel for communicating with the remote desktop. One feature is the clipboard. Open the Guacamole side panel. ](steps-mod01_intro_ex01_get_aboard1/step_4.png)
- PC: Ctrl+Alt+Shift
- Mac: Ctrl+Cmd+Shift

The File Transfer is disabled.

6 A recommended practice is to copy multiple lines of commands from the exercise guide into Pluma at one time.  
![A recommended practice is to copy multiple lines of commands from the exercise guide into Pluma at one time.  ](steps-mod01_intro_ex01_get_aboard1/step_5.png)
When you do copy command lines from a PDF document you must review these commands carefully. The transfer may insert spaces into the command line. This will result in an error.

Review the placement of the backslash \. The backslash \ is a Linux escape character and if improperly paced it will result in an error.

The backslash at the end of the line escapes the return and continues to the next line. Recommend removing the backslash to create a single command line.

7 Edit commands in Pluma. When ready use either the menu Edit > Copy and Edit > Paste or the keyboard Ctl+C and Shift+Ctl+V to transfer commands to the Mate Terminal.
![Edit commands in Pluma. When ready use either the menu Edit > Copy and Edit > Paste or the keyboard Ctl+C and Shift+Ctl+V to transfer commands to the Mate Terminal.](steps-mod01_intro_ex01_get_aboard1/step_6.png)

8 Click Workspace 2.

9 Reference Information
The following documents provide information related to this exercise.

- TBD

10 Use your normal copy and paste commands to copy a line of text into the Guacamole clipboard.
![Use your normal copy and paste commands to copy a line of text into the Guacamole clipboard. ](steps-mod01_intro_ex01_get_aboard1/step_9.png)
- PC: Copy Ctrl+C Paste Ctrl+V
- Mac: Copy Cmd+C Paste Cmd+V

11 In the remote desktop use Ctrl+V to paste. You can paste directly into Web UI, such as Pluma. You cannot paste directly into the Mate Terminal.
![In the remote desktop use Ctrl+V to paste. You can paste directly into Web UI, such as Pluma. You cannot paste directly into the Mate Terminal.](steps-mod01_intro_ex01_get_aboard1/step_10.png)

12 Click Pluma. Pluma is a graphical text editor. It may be used on text files instead of vi. However, one of the primary uses is to copy and paste text from the local desktop.
![Click Pluma. Pluma is a graphical text editor. It may be used on text files instead of vi. However, one of the primary uses is to copy and paste text from the local desktop.](steps-mod01_intro_ex01_get_aboard1/step_11.png)

13 Click Firefox. The Firefox bookmark tool bar shows three short cuts. Cloudera Docs for CDP Base, FreeIPA server, and Cloudera Manager. Click to open all three. Do not log currently.
![Click Firefox. The Firefox bookmark tool bar shows three short cuts. Cloudera Docs for CDP Base, FreeIPA server, and Cloudera Manager. Click to open all three. Do not log currently.](steps-mod01_intro_ex01_get_aboard1/step_12.png)

14 Take time to explore the remote desktop. Open and close tools. Use the Mate Terminal. Ensure you are comfortable with this environment.
## This is a test of MarkDown

### This is a test of MarkDown

#### This is a test of MarkDown

15 Copy and paste the ls commands into Guacamole and then into Pluma.
![Copy and paste the ls commands into Guacamole and then into Pluma. ](steps-mod01_intro_ex01_get_aboard1/step_14.png)
------

The training_materials directory contains supporting courseware

% ls ~/training_materials/security/

The data directory contains the datasets for the course.

% ls /var/data

------

You should remove any current commands from the Guacamole clipboard.

16 Close the Guacamole side panel.
> PC: Ctrl+Alt+Shift

> Mac: Ctrl+Cmd+Shift

17 Click to open a Mate Terminal. The user training is superuser for the exercise environment. The user training has sudo access to root without a password. The user training can log in to any host with ssh without a password.
![Click to open a Mate Terminal. The user training is superuser for the exercise environment. The user training has sudo access to root without a password. The user training can log in to any host with ssh without a password.](steps-mod01_intro_ex01_get_aboard1/step_16.png)
    ~~~
    % sudo su -l
    # exit
    % ssh edge.example.com
    % exit
