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
      <td style="text-align:left"><code>$avatar</code>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">User</td>
    </tr>
    <tr>
      <td style="text-align:left"><code>$bug</code>
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
      <td style="text-align:left"><code>$order</code>
      </td>
      <td style="text-align:left"><code>$o</code>
      </td>
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
  </tbody>
</table>

### Team Commands

| Command | Alias\(es\) | Rank |
| :--- | :--- | :--- |
| `$claim` | `$c` | Junior Employee |
| `$deliver` | `$d` | Junior Employee |
| `$deliverymessage` | `$deliverymsg` | Junior Employee |
| `$fire` |  | Supervisor |
| `$hire` |  | Supervisor |
| `$orderinfo` | `$oinfo` | Junior Employee |
| `$pack` | `$p` | Junior Employee |
| `$strike` |  | Employee |

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
      <td style="text-align:left">Chairman</td>
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
      <td style="text-align:left">Chairman</td>
    </tr>
  </tbody>
</table>

## Commands Details

{% hint style="info" %}
`<>` means optional.  
`[]` means required.  
Don't include them in your commands.
{% endhint %}

### $avatar

Description: _Shows the avatar of the user, mentioned user or provided user ID._  
Usage: `$avatar <user>`

### $bug

Description: _Reports a bug to the developers._  
Usage: `$bug [description]`

### $cancel

Description: _Cancels the current order._  
Usage: `$cancel`

### $claim

Description: _Claims the selected order._  
Usage: `$claim [order_id]`

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

