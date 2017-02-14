1) $('.profile-image').attr('src', 'http://placekitten.com/g/400/600')

2) $('#left-image > img').attr('src', 'http://placekitten.com/g/100/100')

3) $('h1').text('Hello world!')

4)$('#employment > h3').text('Work Info')

5) $('#time-travel').parent().remove()

6) $('body').css('color', 'red')

7) $('.highlight').css('color', 'blue')

8) $('h1').css('font-family', 'monospace')

9)$('.action-icon-bg').css('background-color', 'red')

10)$('#name').attr('placeholder', 'Identify Yourself')

11)$('#message').attr('placeholder', 'State your business')

12)$('#name').attr('value', 'Your nemesis')

13)$('#email').attr('value', 'koalathebear@gmail.com')

14)$('#submit').attr('value', 'En garde!')

15)$('#submit').attr('disabled', 'disabled')

16) $('.bio-info-value').empty()

17) $('#right-image > img').clone().insertAfter('form')

 18) for (var i=0; i<10; i++) { $('#right-image > img').clone().insertAfter('form') }

 19)var listItem = document.createElement('li');
  var leftSpan = document.createElement('span');
  var lastUpdated = document.createTextNode('Page last updated on');
  var rightSpan = document.createElement('span');
  var date = document.createTextNode(Date());
  leftSpan.appendChild(lastUpdated);
  rightSpan.appendChild(date);
  listItem.appendChild(leftSpan);
  listItem.appendChild(rightSpan);
  ('ul.bio-info').append(listItem);
