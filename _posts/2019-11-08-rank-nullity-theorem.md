---
title: Rank-nullity theorem
tags: algebra linear-algebra
layout: article
---
<blockquote class="statement"><p><strong>Rank-nullity theorem</strong> Let V, W be vector spaces, when V is finite dimensional.<span class="intersentencespace"></span> Let T:V<span class="inline_math">\( \to \)</span>W be a linear transformation.<span class="intersentencespace"></span> Then Rank(T)+Nullity(T)=dimV</p></blockquote><!--more-->
<div style="display: none">$$\DeclareMathOperator{\ima}{Im}$$</div>
<p>Let the basis of <span class="inline_math">\( \ker(T) \)</span> be <span class="inline_math">\( \{u_1,u_2,\ldots u_{n-1},u_n\} \)</span> and the basis of vector space <span class="inline_math">\( V \)</span> be <span class="inline_math">\( \{v_1,v_2,\ldots v_{r-1},v_r\} \)</span>.<span class="intersentencespace"></span> Based on the definition of <span class="inline_math">\( \ker(T) \)</span>, <span class="inline_math">\( \{u_1,u_2,\ldots u_{n-1},u_n\} \)</span> is a set of <em>linearly independent</em> vectors in vector space <span class="inline_math">\( V \)</span>.</p>
<p>Based on <a href="https://www.eurekz.com/post/steinitz-exchange-lemma/" target="_blank" rel="noopener">Steinitz exchange lemma</a>, after rearrangement <span class="inline_math">\( \{u_1,u_2,\ldots u_{n-1},u_n, v_{n+1},\ldots v_{r-1},v_r\} \)</span> is a <em>spanning set</em> for <span class="inline_math">\( V \)</span> with size <span class="inline_math">\( =\dim V \)</span>.<span class="intersentencespace"></span> Therefore, <span class="inline_math">\( \{u_1,u_2, \ldots u_{n-1},u_n,v_{n+1},\ldots v_{r-1},v_r\} \)</span> is a basis for <span class="inline_math">\( V \)</span>.</p>
<p>Therefore, <span class="inline_math">\( \{T(u_1),\ldots T(u_n),T(v_{n+1}),\ldots T(v_r)\} \)</span> is a <em>spanning set</em> for <span class="inline_math">\( \ima(T) \)</span>.<span class="intersentencespace"></span> Since <span class="inline_math">\( \{u_1,\ldots u_n\} \)</span> is a basis of <span class="inline_math">\( \ker(T) \)</span>, <span class="inline_math">\( T(u_1)=T(u_2)=\cdots =T(u_n)=\vec{0} \)</span>.<span class="intersentencespace"></span> So clearly, <span class="inline_math">\( \{T(v_{n+1}),\ldots T(v_r)\} \)</span> is a <em>spanning set</em> for <span class="inline_math">\( \ima(T) \)</span>.<span class="intersentencespace"></span></p>
<div id="li" data-tralics-id="uid1" data-number="1" class="equation">		 \begin{equation} 
		 	\sum_{i=n+1}^r \lambda_i \cdot T(v_i)=T(\sum_{i=n+1}^r \lambda_iv_i)=\vec{0}
		 	\label{li}
		 \end{equation} 
</div><p class="noindent">Thus,</p>
<div id="li’" data-tralics-id="uid2" data-number="2" class="equation">		 \begin{equation} 
			 \sum_{i=n+1}^r \lambda_iv_i \in \ker(T)\Leftrightarrow \sum_{i=n+1}^r \lambda_iv_i=\sum_{t=1}^n \lambda_tu_t \Leftrightarrow \sum_{i=n+1}^r \lambda_iv_i-\sum_{t=1}^n\lambda_tu_t=\vec{0}
			 \label{li'}
		 \end{equation}
</div><p class="noindent">Since <span class="inline_math">\( \{u_1,u_2, \ldots u_{n-1},u_n,v_{n+1},\ldots v_{r-1},v_r\} \)</span> is a basis for <span class="inline_math">\( V \)</span>, the only solution to <a href="#li" class="hyperref">(<span class="ref">1</span>)</a> and <a href="#li’" class="hyperref">(<span class="ref">2</span>)</a> is that <span class="inline_math">\( \forall i, \lambda_i=0. \)</span> Therefore <span class="inline_math">\( \{T(v_{n+1}),\ldots T(v_r)\} \)</span> is a set of <em>linearly independent</em> vectors in <span class="inline_math">\( \ima(T) \)</span>.<span class="intersentencespace"></span> <span class="break"></span></p>
<p><span class="inline_math">\( \Rightarrow \{T(v_{n+1}),\ldots T(v_r)\} \)</span> is a basis for <span class="inline_math">\( \ima(T) \)</span>.<span class="break"></span></p>
<p>
  <span class="inline_math">\( \Rightarrow Rank(T)=n ,~Nullity(T)=r-n,~dimV=r \)</span>
  <span class="break"></span>
</p>
<p>Therefore, Rank(<span class="inline_math">\( T \)</span>)+Nullity(<span class="inline_math">\( T \)</span>)=dim<span class="inline_math">\( V \)</span>.</p>
