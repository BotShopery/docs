---
description: Commands available in Shopery.
---

# Commands

## Commands List

### Public Commands

<table>
  <thead>
    <tr>
      <th style="text-align:left">Command</th>
      <th style="text-align:left">Alias(es)</th>
      <th style="text-align:left">Rank</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><code>$about</code>
      </td>
      <td style="text-align:left">
        <p><code>$info</code>
        </p>
        <p><code>$botinfo</code>
        </p>
        <p><code>$developer</code>
        </p>
      </td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$avatar</code>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$cancel</code>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$discord</code>
      </td>
      <td style="text-align:left">
        <p><code>$work</code>
        </p>
        <p><code>$support</code>
        </p>
        <p><code>$workshop</code>
        </p>
        <p><code>$join</code>
        </p>
        <p><code>$job</code>
        </p>
        <p><code>$complain</code>
        </p>
        <p><code>$report</code>
        </p>
        <p><code>$bug</code>
        </p>
      </td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$help</code>
      </td>
      <td style="text-align:left">
        <p><code>$commands</code>
        </p>
        <p><code>$cmds</code>
        </p>
      </td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$invite</code>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$order</code>
      </td>
      <td style="text-align:left"><code>$o</code>
      </td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$prefix</code>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$premium</code>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$review</code>
      </td>
      <td style="text-align:left"><code>$rate</code>
      </td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$status</code>
      </td>
      <td style="text-align:left"><code>$myorder</code>
      </td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$user</code>
      </td>
      <td style="text-align:left">
        <p><code>$userinfo</code>
        </p>
        <p><code>$ui</code>
        </p>
      </td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$vote</code>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">User</td>
    </tr>
  </tbody>
</table>

### Team Commands

| Command | Alias\(es\) | Rank |
| :--- | :--- | :--- |
| `$claim` | `$c` | Trainee |
| `$delete` | `$del` | Employee |
| `$deliver` | `$d` | Trainee |
| `$deliverymessage` | `$deliverymsg` | Trainee |
| `$fire` |  | Supervisor |
| `$hire` |  | Supervisor |
| `$orderinfo` | `$oinfo` | Trainee |
| `$pack` | `$p` | Trainee |
| `$strike` |  | Supervisor |
| `$trainee` |  | Officer |

### Owner Commands

<table>
  <thead>
    <tr>
      <th style="text-align:left">Command</th>
      <th style="text-align:left">Alias(es)</th>
      <th style="text-align:left">Rank</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><code>$sql</code>
      </td>
      <td style="text-align:left"><code>$query</code>
      </td>
      <td style="text-align:left">Director</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$eval</code>
      </td>
      <td style="text-align:left">
        <p><code>$calc</code>
        </p>
        <p><code>$exec</code>
        </p>
      </td>
      <td style="text-align:left">Director</td>
    </tr>
  </tbody>
</table>

## Commands Details

{% hint style="info" %}
`<>` means optional.  
`[]` means required.  
Don't include them in your commands.
{% endhint %}

### $about

Description: _Gives the bot's description and informations._  
Usage: `$about`

### $avatar

Description: _Shows the avatar of the user, mentioned user or provided user ID._  
Usage: `$avatar <user>`

### $cancel

Description: _Cancels the current order._  
Usage: `$cancel`

### $claim

Description: _Claims the selected order._  
Usage: `$claim [order_id]`

### $delete

Description: _Deletes an order._  
Usage: `$delete [order_id] [reason]`

### $deliver

Description: _Delivers the selected order._  
Usage: `$deliver [order_id]`

### $deliverymessage

Description: _Sets the delivery message._  
Usage: `$deliverymessage <message>`

### $discord

Description: _Shows an invite to the official Discord server._  
Usage: `$discord`

### $eval

Description: _Runs Javascript code._  
Usage: `$eval [code]`

### $fire

Description: _Fires the provided user from the Team._  
Usage: `$fire [user]`

### $help

Description: _Shows the commands list._  
Usage: `$help`

### $hire

Description: _Hires the provided user in the Team._  
Usage: `$hire [user]`

### $invite

Description: _Shows an invite for the bot_  
Usage: `$invite`

### $order

Description: _Orders something and sends it to the workshop._  
Usage: `$order [product]`

{% hint style="danger" %}
Make sure to follow our [Terms of Service](other/tos.md#bot-rules) when you order something.
{% endhint %}

### $orderinfo

Description: _Gives informations about the selected order._  
Usage: `$orderinfo [order_id]`

### $pack

Description: _Packs a claimed order._  
Usage: `$pack [url]`

### $prefix

Description: _Changes the server prefix._  
Usage: `$prefix <prefix>`

### $premium

Description: _Shows information about Premium._  
Usage: `$premium`

### $review

Description: _Gives a review when an order is completed, towards the cashier and deliverer._  
Usage: `$review [product_quality] [delivery_quality] <comment>`

### $sql

Description: _Runs a MySQL query._  
Usage: `$sql [query]`

### $status

Description: _Shows the order's status._  
Usage: `$status`

### $strike

Description: _Strikes and deletes the selected order._  
Usage: `$strike [order_id]`

### $trainee

Description: _Sets a user's Trainee status._  
Usage: `$trainee [type] [user]`

### $user

Description: _Shows information about the user._  
Usage: `user <user>`

### $vote

Description: _Shows the vote link._  
Usage: `$vote`

