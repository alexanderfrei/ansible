
      # get a kerberos ticket for your user
      kinit <YOUR_USER>@<MY.DOMAIN.COM>
      klist
      ansible -i hosts <your_group_host_name> -i inventory.ini -m win_ping
