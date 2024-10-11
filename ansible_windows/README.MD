
      # get a kerberos ticket for your user. Domain must be in CAPITAL
      kinit <YOUR_USER>@<MY.DOMAIN.COM>

      # list current kerberos ticket
      klist

      # ping windows machine
      ansible -i hosts <your_group_host_name> -i inventory.ini -m win_ping
