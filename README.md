Please follow these instructions to install Anaconda3 on your ASC student
account.

1.  Download the Anaconda installation Bash script:

    ```
    wget https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh
    ```

2.  Run installation Bash script:

    ```
    bash Anaconda3-2019.03-Linux-x86_64.sh
    ```

    -   When asked to review the license agreement, press the ENTER key

    -   Use the ENTER key to scroll to the bottom of the agreement

    -   When asked to accept the license type "yes" and hit ENTER

    -   When you see a message that looks like:

        ```
        Anaconda3 will now be installed into this location:
        /home/aubcls80/anaconda3
        
          - Press ENTER to confirm the location
          - Press CTRL-C to abort the installation
          - Or specify a different location below
        ```

        Press the ENTER key.

        The installation will take some time, so be patient.

    -   After several minutes, you should be prompted to
        initialize Anaconda3:

        ```
        Do you wish the installer to initialize Anaconda3
        by running conda init? [yes|no]
        ```

        Type "yes" and hit ENTER
        
    -   When the installation successfully finishes, you should see a message
        like:

        ```
        Thank you for installing Anaconda3!
        
        ===========================================================================
        
        Anaconda and JetBrains are working together to bring you Anaconda-powered
        environments tightly integrated in the PyCharm IDE.
        
        PyCharm for Anaconda is available at:
        https://www.anaconda.com/pycharm
        ```

3.  Log off the ASC, and then log back in.

4.  Remove the installation script

    ```
    rm Anaconda3-2019.03-Linux-x86_64.sh
    ```

You're done. By default, you will now be using the Python executable and all the
Python packages that were installed with Anaconda.
