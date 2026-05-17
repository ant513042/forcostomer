# forcostomer
滴萃系列-滴雞精.虱目魚精
<meta charset="utf-8">

<p>訂購步驟：<br />
①填寫收件資料（一張單只能寄送一個地址，如需寄送兩個地址，請分兩張單填寫）<br />
③選擇所需購買的商品數量<br />


<h2>產品訂購單</h2>

<form id="orderForm">
<p>姓名： <input id="name" name="name" required="" type="text" /></p>

<p>電話： <input id="phone" name="phone" required="" type="tel" /></p>

<p>Email： <input id="email" name="email" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$" placeholder="請輸入正確 Email" required="" title="請輸入有效的電子郵件，如 example@gmail.com" type="email" /></p>

<p>地址： <input id="address" name="address" required="" style="width:80%" type="text" /></p>

<p>您的匯款帳號後五碼： <input id="number" name="number" required="" type="text" /></p>

<table>
	<thead>
		<tr>
			<th>商品圖片</th>
			<th>商品名稱</th>
			<th>單價</th>
			<th>數量</th>
		</tr>
	</thead>
	<tbody><!-- 範例商品 -->
		<tr>
			<td><img alt="鳳梨酥" src="/upload/images/5%20(2).png" style="width: 65px; height: 65px;" /></td>
			<td>鳳梨酥一圓形 550g 12盒/箱</td>
			<td>960</td>
			<td><input class="item" data-name="鳳梨酥一圓形 550g 12盒/箱" data-price="960" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="蔓越莓酥" src="/upload/images/5.png" style="width: 64px; height: 65px;" /></td>
			<td>蔓越莓酥一圓形 550g 12盒/箱</td>
			<td>960</td>
			<td><input class="item" data-name="蔓越莓酥一圓形 550g 12盒/箱" data-price="960" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/5%20(1).png" style="width: 65px; height: 65px;" /></td>
			<td>葡萄鳳梨酥一圓形 550g 12盒/箱</td>
			<td>960</td>
			<td><input class="item" data-name="葡萄鳳梨酥一圓形 550g 12盒/箱" data-price="960" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td>&nbsp;</td>
			<td>送 禮 手 提 紙 袋 1個</td>
			<td>10</td>
			<td><input class="item" data-name="送 禮 手 提 紙 袋 1個" data-price="10" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/16%20(1).png" style="width: 91px; height: 65px;" /></td>
			<td>鳳 梨 酥─彩盒版 250g 12盒/箱</td>
			<td>780</td>
			<td><input class="item" data-name="鳳 梨 酥─彩盒版 250g 12盒/箱" data-price="780" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/16.png" style="width: 91px; height: 65px;" /></td>
			<td>鳳蔓越莓酥─彩盒版 250g 12盒/箱</td>
			<td>780</td>
			<td><input class="item" data-name="蔓越莓酥─彩盒版 250g 12盒/箱" data-price="780" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/16%20(2).png" style="width: 91px; height: 65px;" /></td>
			<td>芒 果 酥─彩盒版 250g 12盒/箱</td>
			<td>780</td>
			<td><input class="item" data-name="芒 果 酥─彩盒版 250g 12盒/箱" data-price="780" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/12%20(2).png" style="width: 97px; height: 65px;" /></td>
			<td>土鳳梨酥─台灣造型 800g 6盒/箱</td>
			<td>1080</td>
			<td><input class="item" data-name="土鳳梨酥─台灣造型 800g 6盒/箱" data-price="1080" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/12%20(4).png" style="width: 146px; height: 65px;" /></td>
			<td>土 鳳 梨 酥 五斤 2盒/箱</td>
			<td>900</td>
			<td><input class="item" data-name="土 鳳 梨 酥 五斤 2盒/箱" data-price="900" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/12%20(5).png" style="width: 133px; height: 65px;" /></td>
			<td>蔓 越 莓 酥 五斤 2盒/箱</td>
			<td>900</td>
			<td><input class="item" data-name="蔓 越 莓 酥 五斤 2盒/箱" data-price="900" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/12%20(3).png" style="width: 146px; height: 65px;" /></td>
			<td>芒 果 酥 五斤 2盒/箱</td>
			<td>900</td>
			<td><input class="item" data-name="芒 果 酥 五斤 2盒/箱" data-price="900" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/250G%20(2).png" style="width: 46px; height: 65px;" /></td>
			<td>鹹 蛋 黃 酥 餅 250g 8袋/箱</td>
			<td>520</td>
			<td><input class="item" data-name="鹹 蛋 黃 酥 餅 250g 8袋/箱" data-price="520" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/250G%20(3).png" style="width: 46px; height: 65px;" /></td>
			<td>起 司 酥 餅 250g 8袋/箱</td>
			<td>520</td>
			<td><input class="item" data-name="起 司 酥 餅 250g 8袋/箱" data-price="520" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/250G.png" style="width: 46px; height: 65px;" /></td>
			<td>鹹 蛋 黃 五穀堅果酥 250g 8袋/箱</td>
			<td>520</td>
			<td><input class="item" data-name="鹹 蛋 黃 五穀堅果酥 250g 8袋/箱" data-price="520" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/250G%20(1).png" style="width: 46px; height: 65px;" /></td>
			<td>黑 芝 麻 酥 餅 250g 8袋/箱</td>
			<td>520</td>
			<td><input class="item" data-name="黑 芝 麻 酥 餅 250g 8袋/箱" data-price="520" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/8%20(6).png" style="width: 45px; height: 65px;" /></td>
			<td>古 早 味 桃 酥 420g 6袋/箱</td>
			<td>390</td>
			<td><input class="item" data-name="古 早 味 桃 酥 420g 6袋/箱" data-price="390" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/9.png" style="width: 29px; height: 65px;" /></td>
			<td>原 味 爆米花 200g 12罐/箱</td>
			<td>780</td>
			<td><input class="item" data-name="原 味 爆米花 200g 12罐/箱" data-price="780" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/9%20(5).png" style="width: 29px; height: 65px;" /></td>
			<td>焦 糖 風 味 爆米花 200g 12罐/箱</td>
			<td>780</td>
			<td><input class="item" data-name="焦 糖 風 味 爆米花 200g 12罐/箱" data-price="780" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/9%20(4).png" style="width: 30px; height: 65px;" /></td>
			<td>起 司 風 味 爆米花 200g 12罐/箱</td>
			<td>780</td>
			<td><input class="item" data-name="起 司 風 味 爆米花 200g 12罐/箱" data-price="780" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/9%20(6).png" style="width: 32px; height: 65px;" /></td>
			<td>巧克力 風味 爆米花 200g 12罐/箱</td>
			<td>780</td>
			<td><input class="item" data-name="巧克力 風味 爆米花 200g 12罐/箱" data-price="780" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/45g%20popcorn%20(2).jpg" style="width: 51px; height: 65px;" /></td>
			<td>原　　味 爆米花　 　45g 12包/箱</td>
			<td>200</td>
			<td><input class="item" data-name="原　　味 爆米花　 　45g 12包/箱" data-price="200" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/45g%20popcorn%20(3).jpg" style="width: 55px; height: 65px;" /></td>
			<td>焦糖風味 風味 爆米花 45g 12包/箱</td>
			<td>200</td>
			<td><input class="item" data-name="焦糖風味 風味 爆米花 45g 12包/箱" data-price="200" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/LINE_ALBUM_%E5%A4%AA%E7%A9%BA%E5%8C%85%E7%88%86%E7%B1%B3%E8%8A%B1_230609_9-removebg-preview.png" style="width: 49px; height: 65px;" /></td>
			<td>可可巧克力風味爆米花 45g 12包/箱</td>
			<td>200</td>
			<td><input class="item" data-name="可可巧克力風味爆米花 45g 12包/箱" data-price="200" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/LINE_ALBUM_%E5%A4%AA%E7%A9%BA%E5%8C%85%E7%88%86%E7%B1%B3%E8%8A%B1_230609_10-removebg-preview.png" style="width: 54px; height: 65px;" /></td>
			<td>熱戀草莓 風味爆米花 45g 12包/箱</td>
			<td>200</td>
			<td><input class="item" data-name="熱戀草莓 風味爆米花 45g 12包/箱" data-price="200" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/%E7%94%98%E7%94%9C%E6%A2%853.png" style="width: 51px; height: 65px;" /></td>
			<td>特 大 甘 甜 梅 190g　12罐/箱</td>
			<td>1200</td>
			<td><input class="item" data-name="特 大 甘 甜 梅 190g　12罐/箱" data-price="1200" min="0" type="number" value="0" /></td>
		</tr>
		<tr>
			<td><img alt="" src="/upload/images/13.png" style="width: 85px; height: 65px;" /></td>
			<td>頂級鳳梨酥禮盒 500g 附提袋 12盒/箱</td>
			<td>2760</td>
			<td><input class="item" data-name="頂級鳳梨酥禮盒 500g 附提袋 12盒/箱" data-price="2760" min="0" type="number" value="0" /></td>
		</tr>
		<!-- 可以依照需求再加入更多商品 -->
	</tbody>
</table>

<p>商品小計： <input id="subtotal" readonly="readonly" type="text" value="0" /> 元</p>

<p>運費（新竹貨運）： <input id="shipping" readonly="readonly" type="text" value="120" /> 元 （滿 3000 元免運）</p>

<p><strong>訂購總金額：</strong> <input id="total" name="total" readonly="readonly" type="text" value="0" /> 元</p>

<p><button type="submit">送出訂單</button></p>
</form>
<script>
const items = document.querySelectorAll('.item');
const subtotalInput = document.getElementById('subtotal');
const shippingInput = document.getElementById('shipping');
const totalInput = document.getElementById('total');

function calcTotal() {
  let subtotal = 0;
  items.forEach(item => {
    const qty = Number(item.value) || 0;
    const price = Number(item.dataset.price) || 0;
    subtotal += qty * price;
  });

  let shipping = 0;
  if (subtotal > 0 && subtotal < 3000) shipping = 120;

  subtotalInput.value = subtotal;
  shippingInput.value = shipping;
  totalInput.value = subtotal + shipping;
}

// 監聽數量變化
items.forEach(item => item.addEventListener('input', calcTotal));
calcTotal(); // 頁面載入先計算一次

document.getElementById('orderForm').addEventListener('submit', function(e){
  e.preventDefault();

  const emailValue = document.getElementById('email').value;
  // 簡單檢查 Email 格式
  if (!emailValue.match(/^[^\s@]+@[^\s@]+\.[^\s@]+$/)) {
    alert("請輸入有效的 Email");
    return;
  }

  let orderText = '';
  items.forEach(item => {
    const qty = Number(item.value) || 0;
    const price = Number(item.dataset.price) || 0;
    if (qty > 0) {
      orderText += `${item.dataset.name} x ${qty}（$${price}）\n`;
    }
  });

  if (orderText === '') {
    alert("請至少選擇一樣商品");
    return;
  }

  emailjs.send(
    "service_e9p1mas",
    "template_rlpw265",
    {
      name: document.getElementById("name").value,
      phone: document.getElementById("phone").value,
      email: emailValue,
      address: document.getElementById("address").value,
      number: document.getElementById("number").value,
      order: orderText,
      subtotal: subtotalInput.value,
      shipping: shippingInput.value,
      total: totalInput.value,
      cc_email: emailValue // 送確認信給填寫的 Email
    }
  ).then(function(){
    alert("訂單送出成功！\n匯款完再麻煩來電告知 06-2662226");
    location.reload();
  }, function(error){
    alert("寄送失敗，請稍後再試\n" + error.text);
  });
});
</script>
