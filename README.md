# C.H-Chatlock

### User Chat can be set to True or False

### 유저 채팅 여부를 참, 거짓으로 설정할 수 있습니다.
----------------------------------------------------
## How to use?

<pre>
<code>/chatlock yes
</pre></code>

#### Can User Chat.

<pre>
<code>/chatlock no
</pre></code>

#### Can't User Chat.
----------------------------------------------------
## Program principle

<pre><code>/chatlock yes -> **player_chat = true** -> if(get_value(chat) == true) -> "Can't Use Chat" massage and cancel() -> <Can't Use Chat></pre></code>

Set the value of the "player_chat" variable to True.

If "Player_chat" variable is true, Cancel.


<pre><code>/chatlock no -> **player_chat = null** -> <Can Use Chat></pre></code>

Clear value of the "player_chat" variable.

No chat-related code will work. Can chat

------------------------------------------------------

## 어떻게 사용합니까?

<pre>
<code>/chatlock yes
</pre>
</code>

#### 입력시 채팅할 수 있습니다.

<pre>
<code>/chatlock no
</pre>
</code>

#### 입력시 채팅할 수 없습니다.
----------------------------------------------------
## 작동원리

<pre><code>/chatlock yes -> **player_chat = true** -> if(get_value(chat) == true) -> "Can't Use Chat" massage and cancel() -> <Can't Use Chat></pre></code>

"player_chat" 변수의 값이 참일때, 채팅금지 메세지와 함께 캔슬합니다.


<pre><code>/chatlock no -> **player_chat = null** -> <Can Use Chat></pre></code>

"player_chat" 변수의 값을 초기화합니다.

아무런 채팅관련 코드가 작동되지 않아, 그대로 채팅을 사용할 수 있습니다.
