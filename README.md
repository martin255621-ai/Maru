-- ====================================================================
-- DEOBFUSCATED RECOVERED SOURCE: _spy_target_1792288888701.luau
-- Total Closures / Modules: 11
-- ====================================================================

local Modules = {}

-- Module [46] (4,773 bytes)
Modules[46] =
function(f, X, X_2, l, Y, Y_2, D, D_2, E, k, t, t_2, t_3, t_4, g)
    local F,T,K,s,S,w,A,N,R,y,c,v,z,C,a=f[31],f[52],f[37],f[112],f[114],f[23],f[61],f[88],f[86],f[120],f[12],f[65],f[9],f[77],f.bt
    local function G(Q)
        local H,o,V,M,b,W,I,P,Z,h,j,q,U,e,_=F,T,K,s,S,w,A,N,R,y,c,v,z,C,a
        local function F(...)
            local T=H
            local K,s,S,w,A=T(t),g,k
            local k,t,g,N,R,y,c,v,z,C,a,H=M,W,b,V,I,P,Z,h,j,q,U,e
            local V,M,b,W,I=o(function(...)
                local o,P,Z
                while true do local h=D[S]
                local j=h>=4
                if j then
                    local j=h<6
                    if j then
                        local j=h==5
                        if j then
                            local j
                            j,s=nil,s+1
                            local q=s
                            K[q]=X[S]
                            S+=1
                            K[E[S]]=K[s]
                            s-=1
                            S+=1
                            s+=1
                            q=s
                            K[q]=X[S]
                            S+=1
                            s+=1
                            K[s]=K
                            S+=1
                            s+=1
                            q=s
                            K[q]=X[S]
                            S+=1
                            s+=1
                            q=s
                            K[q]=X[S]
                            S+=1
                            local U,e,O,p,x=X[S],w,A
                            if U then
                                q=#U/3
                                if q>0 then
                                    j,p,x={},e,O
                                    for d=1,q,1 do local q=(d-1)*3
                                    local i,u=U[q+3],U[q+2]
                                    if i==1 then
                                        p=if not p then{}else p
                                        local B=p[u]
                                        if not B then
                                        B={[4]=K,[6]=u}
                                        p[u]=B
                                        j[d]=B
                                    else if i==3 then
                                        j[d]=K[u]
                                    else if i==0 then
                                        j[d]=Q[u]
                                    else if i==2 then
                                        x=if not x then{}else x
                                        local i=x[u]
                                        if not i then
                                        i={[5]=U[q+1],[6]=u,[4]=K}
                                        x[u]=i
                                        j[d]=i
                                        end
                                        end
                                        end
                                        end
                                    else p,x=e,O
                                    end
                                else p,x=e,O
                                end
                                w,A=p,x
                                e=s
                                K[e]=K[e](j,nil,nil)
                                S+=1
                                s+=1
                                x=s
                                K[x]=X[S]
                                o=j
                            else s+=1
                                local j=s
                                K[j]=X[S]
                                S+=1
                                s+=1
                                j=s
                                K[j]=K[E[S]]
                                S+=1
                                j=s
                                o=K[j-E[S]]
                                s+=1
                                K[s]=o
                                S+=1
                                j=s
                                o=K[j-E[S]]
                                s+=1
                                K[s]=o
                                S+=1
                                s+=1
                                j=s
                                K[j]=X[S]
                                S+=1
                                s+=1
                                j=s
                                K[j]=E[S]
                                S+=1
                                o,P=E[S],K[s]
                                s-=1
                                Z=s-o
                                o,s=N(K[Z](k(K,Z+1,s))),Z+P-1
                                g(o,1,P,Z,K)
                                S+=1
                                j=s
                                o=K[j-E[S]]
                                s+=1
                                K[s]=o
                                S+=1
                                s+=1
                                j=s
                                K[j]=K[E[S]]
                                S+=1
                                s+=1
                                j=s
                                K[j]=E[S]
                                S+=1
                                o,P=E[S],K[s]
                                s-=1
                                Z=s-o
                                o,s=N(K[Z](k(K,Z+1,s))),Z+P-1
                                g(o,1,P,Z,K)
                                S+=1
                                local q,U=w,A
                                if q then
                                    for e in t,q,nil do if q then
                                        j=q[e]
                                        if j then
                                        j[4]=j
                                        j[5]=K[e]
                                        j[6]=5
                                        q[e]=nil
                                        end
                                    end
                                end
                            end
                            if U then
                                for e,O in t,U,nil do q=O[5]
                                if U then
                                    j=U[e]
                                    if j then
                                        local O,p=e+q,T(q)
                                        g(K,e,O-1,1,p)
                                        j[4]=p
                                        j[6]=1
                                        U[e]=nil
                                    end
                                end
                            end
                        end
                        o=E[S]
                        if o==0 then
                            return false,false
                        end
                        P=s-o+1
                        q=s
                        return false,false,P,q
                    end
                else local j=h<7
                    if j then
                        local j
                        j,s=nil,s+1
                        local q=s
                        K[q]=X[S]
                        S+=1
                        K[E[S]]=K[s]
                        s-=1
                        S+=1
                        s+=1
                        q=s
                        K[q]=X[S]
                        S+=1
                        s+=1
                        K[s]=K
                        S+=1
                        s+=1
                        q=s
                        K[q]=X[S]
                        S+=1
                        s+=1
                        q=s
                        K[q]=X[S]
                        S+=1
                        local U,e,O,p,x=X[S],w,A
                        if U then
                            q=#U/3
                            if q>0 then
                                j,p,x={},e,O
                                for d=1,q,1 do local i=(d-1)*3
                                local u,B=U[i+3],U[i+2]
                                if u==1 then
                                    p=if not p then{}else p
                                    local m=p[B]
                                    if not m then
                                        m={[4]=K,[6]=B}
                                        p[B]=m
                                        j[d]=m
                                    else if u==3 then
                                        j[d]=K[B]
                                    else if u==0 then
                                        j[d]=Q[B]
                                    else if u==2 then
                                        x=if not x then{}else x
                                        local u=x[B]
                                        if not u then
                                        u={[5]=U[i+1],[6]=B,[4]=K}
                                        x[B]=u
                                        j[d]=u
                                        end
                                        end
                                        end
                                        end
                                    else p,x=e,O
                                    end
                                else p,x=e,O
                                end
                                w,A=p,x
                                e=s
                                K[e]=K[e](j,nil,nil)
                                S+=1
                                s+=1
                                U=s
                                K[U]=X[S]
                                S+=1
                                s+=1
                                O=s
                                K[O]=X[S]
                                S+=1
                                s+=1
                                x=s
                                K[x]=K[E[S]]
                                S+=1
                                q=s
                                o=K[q-E[S]]
                                s+=1
                                K[s]=o
                                S+=1
                                x=s
                                o=K[x-E[S]]
                                s+=1
                                K[s]=o
                                S+=1
                                s+=1
                                p=s
                                K[p]=X[S]
                                S+=1
                                s+=1
                                O=s
                                K[O]=E[S]
                            else local j=h~=8
                                if j then
                                    s+=1
                                    local j=s
                                    K[j]=Q[E[S]]
                                    S+=1
                                    s+=1
                                    j=s
                                    K[j]=X[S]
                                else o,P,Z=E[S]+1,E[S+1],E[S+2]
                                    for j=1,Z,1 do P=c(y(P,(R(P,13))),536870911)
                                    P=y(P,(v(P,13)))
                                    P=c(y(P,(R(P,14))),536870911)
                                    E[o]=y(E[o],(c(v(P,0),127)))
                                    D[o]=y(D[o],(c(v(P,7),127)))
                                    o=o+1
                                end
                                D[S]=0
                                S+=2
                            end
                        end
                    end
                else local R=h<2
                    if R then
                        local R=h~=1
                        if not(R)then s+=1
                        local R=s
                        K[R]=Q[E[S]]
                        S+=1
                        s+=1
                        R=s
                        K[R]=X[S]
                    end
                else local X=h==3
                    if X then
                        o,P=E[S],K[s]
                        s-=1
                        Z=s-o
                        o,s=N(K[Z](k(K,Z+1,s))),Z+P-1
                        g(o,1,P,Z,K)
                        S+=1
                        local X=s
                        o=K[X-E[S]]
                        s+=1
                        K[s]=o
                        S+=1
                        s+=1
                        X=s
                        K[X]=K[E[S]]
                        S+=1
                        s+=1
                        X=s
                        K[X]=E[S]
                        S+=1
                        o,P=E[S],K[s]
                        s-=1
                        Z=s-o
                        o,s=N(K[Z](k(K,Z+1,s))),Z+P-1
                        g(o,1,P,Z,K)
                        S+=1
                        local N,R=w,A
                        if N then
                            for Q in t,N,nil do if N then
                                X=N[Q]
                                if X then
                                    X[4]=X
                                    X[5]=K[Q]
                                    X[6]=5
                                    N[Q]=nil
                                end
                            end
                        end
                    end
                    if R then
                        for Q,Z in t,R,nil do N=Z[5]
                        if R then
                            X=R[Q]
                            if X then
                                local Z,h=Q+N-1,T(N)
                                g(K,Q,Z,1,h)
                                X[4]=h
                                X[6]=1
                                R[Q]=nil
                            end
                        end
                    end
                end
                o=E[S]
                if o==0 then
                    return false,false
                end
                P=s-o+1
                N=s
                return false,false,P,N
            else o=E[S]
                local X,s,N=v(o,8),c(o,255),l[4]
                local R=y(N[X],380445389)
                N[X]=R
                X,N=l[7],R+1
                R=z(X,N)
                local l,c
                if R<128 then
                    l,c=R,N+1
                else local v=z(X,N+1)
                    if v<128 then
                        l,c=R-128+v*128,N+2
                    else local Q=z(X,N+2)
                        if Q<128 then
                            l,c=R-128+(v-128)*16384+Q*128,N+3
                        else local o=z(X,N+3)
                            l,c=(R-128)*2097152+(v-128)*16384+(Q-128)+o%128*128+(o-o%128)*2097152,N+4
                        end
                    end
                end
                N,R=s*16843009,c+l
                local v=R-l%4
                for l=c,v-1,4 do C(X,l,(y(a(X,l),N)))
            end
            for l=v,R-1,1 do H(X,l,(y(z(X,l),s)))
        end
        v=S
        E[v],D[v]=16,0
    end
end
end
S+=1
end
end,...)
if V then
    if M then
        if b then
            return K[W](k(I,1,I.n))
        else return K[W](k(K,W+1,I))
        end
    elseif W then
            if b then
                return k(W,1,W.n)
            else return k(K,W,I)
            end
        end
    else local X,l,D=w,A,K
        if X then
            for E in t,X,nil do if X then
                local k=X[E]
                if k then
                    k[4]=k
                    k[5]=D[E]
                    k[6]=5
                    X[E]=nil
                end
            end
        end
    end
    if l then
        for E,k in t,l,nil do X=k[5]
        if l then
            k=l[E]
            if k then
                local t=T(X)
                g(D,E,E+X-1,1,t)
                k[4]=t
                k[6]=1
                l[E]=nil
            end
        end
    end
end
_(f,M,S,Y)
end
end
return F
end
return G
end

-- Module [109] (1,670 bytes)
Modules[109] =
function(f, X, X_2, X_3)
    return function(X, l)
        local l=X[1]
        local Y=X[2]
        local D=X[3]
        return function()
            local X,E,k,t,g,F,T,K,s,S,w,A,N,R,y=11
            while true do local c,v,z=X<=5
            if c then
                if X<=2 then
                    if X<=0 then
                        local c=f[86](y,255)
                        S[R],S[c]=S[c],S[R]
                        local C=f[29](k,g,F,t,(f[61](S[f[86](S[R]+S[c],255)],24)))
                        f[65](w,N,(f[88](f[9](T,K+N),C)))
                        X,k,t,g,F=6,R,c,R,c
                    elseif X<=1 then
                            v=f[86](g+1,255)
                            z=f[86](F+S[v],255)
                            S[v],S[z]=S[z],S[v]
                            local c=S[f[86](S[v]+S[z],255)]
                            f[77](w,k,(f[88](f[12](T,K+k),c)))
                            X,g,F=9,v,z
                        else local c,C=0,f[86](g+1,255)
                            local a=f[86](F+S[C],255)
                            S[C],S[a]=S[a],S[C]
                            X,k,t,g,F=5,c,a,f[61](S[f[86](S[C]+S[a],255)],0),C+1
                        end
                    elseif X<=3 then
                            local c,C=s-1,1+0
                            local a={nil,A-C,c+0,C,E}
                            X,E=9,a
                        elseif X<=4 then
                                local c=f[86](t+S[R],255)
                                S[R],S[c]=S[c],S[R]
                                local C
                                t,X,C=f[61](S[f[86](S[R]+S[c],255)],16),0,f[86](R+1,255)
                                R,y=C,c+S[C]
                            else local y=f[86](F,255)
                                local c=f[86](t+S[y],255)
                                S[y],S[c]=S[c],S[y]
                                local C
                                F,X,t,C=f[61](S[f[86](S[y]+S[c],255)],8),4,c,f[86](y+1,255)
                                R=C
                            end
                        else local t=X<=8
                            if t then
                                if X<=6 then
                                    local t,R,y=E[1],E[5],E[2]
                                    local c,C=t+R,R<=0
                                    t,R=c>=y,c<=y
                                    y=C and t or not C and R
                                    E[1]=c
                                    if y then
                                        X,N=2,c
                                    else X=8
                                    end
                                elseif X<=7 then
                                        return w
                                    else local t=E[3]
                                        X,E=3,t
                                    end
                                else local t=X<=9
                                    if t then
                                        local t,N,R=E[2],E[4],E[3]
                                        local y,c=t+N,N<=0
                                        N,t=y>=R,y<=R
                                        R=c and N or not c and t
                                        E[2]=y
                                        if R then
                                        X,k=1,y
                                    else X=10
                                        end
                                    else local k=X<=10
                                        if k then
                                        local k=E[5]
                                        X,E=7,k
                                    else local k
                                        local k,t=l[4][l[6]]
                                        local l=Y[4][Y[6]]
                                        local Y,t,t,N,R=f[40](k)-l
                                        t,v,z,N,R=D[4][D[6]],0,0,f[11](Y),Y-Y%4
                                        local f,D=R-1,4+0
                                        local y,c=0-D
                                        c,X={y,f+0,E,nil,D},6
                                        E,g,F,T,K,s,S,w,A=c,0,0,k,l,Y,t,N,R
                                        end
                                    end
                                end
                            end
                        end
                    end
                end
            end

            -- Module [16] (9,408 bytes)
            Modules[16] =
            function(f, X, l, Y, D, D_2, D_3, D_4, E, k, t, t_2, g, g_2, F, T, T_2, T_3)
                local T,K,s,S,w,A,N,R,y,c,v,z,C=f[31],f[61],f[88],f[86],f[120],f[114],f[37],f[112],f[29],f[12],f[65],f[9],f[77]
                return function(a)
                    local a,G,Q,H,o,V,M,b,W,I,P,Z,h=T,K,s,S,w,A,N,R,y,c,v,z,C
                    return function(...)
                        local T
                        local K,s,S=3394503699,1283910884,a(g)
                        local g
                        local w,A,N,R,y,c,v=4262881929
                        if t==154 then
                            y,c,v=k,F,t
                            while true do local z=D[y]
                            if z>=6 then
                                if z<9 then
                                    if z<7 then
                                        c+=1
                                        S[c]=nil
                                    else if z==8 then
                                        N=S[c]
                                        y,c=N,c-1
                                    else N,g,R=E[y]+1,E[y+1],E[y+2]
                                        for C=1,R,1 do g=H(Q(g,(G(g,13))),536870911)
                                        g=Q(g,(o(g,13)))
                                        g=H(Q(g,(G(g,14))),536870911)
                                        E[N]=Q(E[N],(H(o(g,0),127)))
                                        D[N]=Q(D[N],(H(o(g,7),127)))
                                        N=N+1
                                        end
                                        D[y]=0
                                        y=y+2
                                    end
                                end
                            else local C=y
                                if z<10 then
                                    v=S[c]
                                    c-=1
                                    y=Q(E[C],(H(Q(D[C],3),127)))+1
                                    break
                                elseif z~=11 then
                                        c+=1
                                        S[c]=S[Q(E[C],(H(Q(v,120),127)))]
                                    else c+=1
                                        S[c]=E[C]
                                    end
                                end
                            else if z>=3 then
                                    if z>=4 then
                                        if z~=5 then
                                        S[Q(E[y],(H(v,127)))]=S[c]
                                        c=c-1
                                    else N={...}
                                        V(N,1,Q(E[y],(H(y,127))),1,S)
                                        end
                                    else c+=1
                                        S[c]=l[y]
                                    end
                                else if z<1 then
                                    else if z~=2 then
                                        c+=1
                                        S[c]=Q(E[y],(H(Q(D[y],109),127)))
                                    else y=Q(E[y],(H(D[y],127)))
                                        end
                                    end
                                end
                            end
                            y=y+1
                        end
                    else c,y,v=F,k,t
                    end
                    if v==215 then
                        N,g,R=D[y]+1,D[y+1],D[y+2]
                        for l=1,R,1 do g=H(Q(g,(G(g,13))),536870911)
                        g=Q(g,(o(g,13)))
                        g=H(Q(g,(G(g,14))),536870911)
                        D[N]=Q(D[N],(H(o(g,0),127)))
                        E[N]=Q(E[N],(H(o(g,7),127)))
                        N=N+1
                    end
                    E[y]=3
                    y=y+2
                end
            end
        end
        y=y+1
        eif v==169 then
            v=S[c]
            c-=1
            y=Q(E[k],64)+1
            break
        else c+=1
            S[c]=Q(E[k],(H(Q(v,k,D[k]),127)))
        end
    end
else if l>=2 then
        if l~=3 then
        else N=S[c]
            y,c=N,c-1
        end
    else if l~=1 then
            y=Q(E[y],(H(Q(D[y],v,65),127)))
        else S[Q(E[y],(H(v,127)))]=S[c]
            c=c-1
        end
    end
end
y=y+1
eif v==64 then
    while true do local l=E[y]
    if l>=41 then
        if l<62 then
            if l<51 then
                if l>=46 then
                    if l>=48 then
                        if l<49 then
                            c+=1
                            S[c]=X[y]
                        else if l~=50 then
                                if S[c]then c-=1
                                y=Q(D[y],(H(Q(v,7),127)))
                            else c+=1
                                S[c]=D[y]
                            end
                        end
                    else if l~=47 then
                            c+=1
                            S[c]=nil
                        else N=S[c]
                            c-=1
                            S[c]=S[c]>=N
                        end
                    end
                else if l<43 then
                        if l==42 then
                            c+=1
                            S[c]={}
                        else N=S[c]
                            y,c=N,c-1
                        end
                    else if l<44 then
                            N=S[c]
                            c-=1
                            S[c]=S[c][N]
                        else if l~=45 then
                                N,g=Q(D[y],(H(Q(E[y],y),127))),S[c]
                                c-=1
                                R=c-N
                                S[R]=M(S[R](b(S,R+1,c)))
                                c=R
                            else c+=1
                                S[c]=S[D[y]]
                                y+=1
                                c+=1
                                S[c]=X[y]
                            end
                        end
                    end
                end
            else if l>=56 then
                    if l>=59 then
                        if l<60 then
                            N,c=S[c],F+1
                            S[F+1]=N
                        else if l~=61 then
                                K=S[c]
                                c=c-1
                            else c+=1
                                S[c]=X[y]
                                y+=1
                                N=S[c]
                                c-=1
                                S[c]=S[c]<=N
                            end
                        end
                    else if l<57 then
                            S[Q(D[y],(H(Q(E[y],y,36),127)))+S[c-1]]=S[c]
                            c=c-2
                        else if l==58 then
                                if not S[c]then y=Q(D[y],(H(Q(v,E[y],46),127)))
                            else c=c-1
                            end
                        else c+=1
                            S[c]=S[D[y]]
                            y+=1
                            c+=1
                            S[c]=S[D[y]]
                        end
                    end
                end
            else if l>=53 then
                    if l>=54 then
                        if l~=55 then
                            c+=1
                            S[c]=K
                        else N=S[c-D[y]]
                            c+=1
                            S[c]=N
                            y+=1
                            c+=1
                            S[c]=S[D[y]]
                        end
                    else N=S[c]
                        c-=1
                        S[c]=W(S[c],N)
                    end
                else if l==52 then
                        N,g,R=D[y]+1,Q(D[y+1],(H(Q(s,(H(o(s,29),7))),536870911))),D[y+2]
                        for k=1,R,1 do g=H(Q(g,(G(g,13))),536870911)
                        g=Q(g,(o(g,13)))
                        g=H(Q(g,(G(g,14))),536870911)
                        D[N]=Q(D[N],(H(o(g,0),127)))
                        E[N]=Q(E[N],(H(o(g,7),127)))
                        N=N+1
                    end
                    E[y]=79
                    y=y+2
                else c+=1
                    S[c]=f[Q(D[y],(H(E[y],127)))]
                end
            end
        end
    end
else if l>=72 then
        if l<77 then
            if l<74 then
                if l==73 then
                    c+=1
                    S[c]=X[y]
                    y+=1
                    c+=1
                    S[c]=S[D[y]]
                else N=S[c]
                    c-=1
                    for f=Q(D[y],(H(Q(v,y),127))),Q(D[y],(H(Q(v,y),127)))+N-1,1 do S[f]=nil
                end
            end
        else if l>=75 then
                if l==76 then
                    N=S[c]
                    c-=1
                    S[c]=S[c]/N
                else y,c=if S[c]then Q(D[y],(H(Q(v,E[y]),127)))else y,c-1
                end
            else N=S[c-Q(D[y],(H(Q(5,y,E[y]),127)))]
                c+=1
                S[c]=N
            end
        end
    else if l<80 then
            if l<78 then
                N,g,R=S[c],S[c-1],S[c-2]
                c-=3
                R[g]=N
            else if l==79 then
                else N=S[c]
                    c-=1
                    S[c]=S[c]..N
                end
            end
        else if l>=81 then
                if l==82 then
                    N=S[c]
                    c+=1
                    S[c]=N
                else N,g,R=D[y]+1,Q(D[y+1],(H(Q(K,(H(o(K,29),7))),536870911))),D[y+2]
                    for f=1,R,1 do g=H(Q(g,(G(g,13))),536870911)
                    g=Q(g,(o(g,13)))
                    g=H(Q(g,(G(g,14))),536870911)
                    D[N]=Q(D[N],(H(o(g,0),127)))
                    E[N]=Q(E[N],(H(o(g,7),127)))
                    N=N+1
                end
                E[y]=79
                y=y+2
            end
        else N,g=D[y],Q(s,H(o(s,14),262143),(H(o(s,28),15)))
            R=N<16384 and 7 or(N<2097152 and 14 or 21)
            A,T=H(N,G(1,R)-1),o(N,R)
            D[y]=Q(A,27,(H(g,127)))
            E[y]=Q(T,50,(H(o(g,7),127)))
            y=y-1
        end
    end
end
else if l<67 then
    if l<64 then
        if l==63 then
            S[c]=not S[c]
        else N=S[c]
            c-=1
            S[c]=S[c]<N
        end
    else if l<65 then
            c+=1
            S[c]=s
        else if l~=66 then
                c=c-Q(D[y],(H(Q(v,y),127)))
            else if S[c]then y=Q(D[y],(H(E[y],127)))
            else c=c-1
            end
        end
    end
end
else if l<69 then
    if l==68 then
        w=S[c]
        c=c-1
    else c+=1
        S[c]=S[D[y]]
        y+=1
        N=S[c-D[y]]
        c+=1
        S[c]=N
    end
else if l>=70 then
        if l==71 then
            N=S[c-D[y]]
            c+=1
            S[c]=N
            y+=1
            N=S[c-D[y]]
            c+=1
            S[c]=N
        else N,g=Q(D[y],(H(E[y],127))),S[c]
            c-=1
            R=S[c-g]
            V(S,c-g+1,c,N+1,R)
            c=c-g
        end
    else c+=1
        S[c]=S[D[y]]
        y+=1
        c+=1
        S[c]=S[D[y]]
        y+=1
        c+=1
        S[c]=S[D[y]]
    end
end
end
end
end
else if l>=20 then
    if l>=30 then
        if l<35 then
            if l>=32 then
                if l>=33 then
                    if l~=34 then
                        S[D[y]]=S[c]
                        c-=1
                        y+=1
                        S[D[y]]=S[c]
                        c-=1
                        y+=1
                        S[D[y]]=S[c]
                        c-=1
                        y+=1
                        S[D[y]]=S[c]
                        c=c-1
                    else c+=1
                        S[c]=w
                    end
                else N=S[c]
                    c-=1
                    S[c]=S[c]==N
                end
            else if l==31 then
                    S[D[y]]=S[c]
                    c-=1
                    y+=1
                    S[D[y]]=S[c]
                    c-=1
                    y+=1
                    S[D[y]]=S[c]
                    c=c-1
                else N=S[c]
                    c-=1
                    S[c]=S[c]<=N
                end
            end
        else if l>=38 then
                if l>=39 then
                    if l~=40 then
                        c+=1
                        S[c]=S[D[y]]
                        y+=1
                        c+=1
                        S[c]=S[D[y]]
                        y+=1
                        c+=1
                        S[c]=S[D[y]]
                        y+=1
                        c+=1
                        S[c]=S[D[y]]
                    else local f,k=S[c]
                        repeat local t=f%4294967296
                        if t~=t then
                            k=0
                            break
                        end
                        k=t-t%1
                    until true
                    S[c]=k
                end
            else N=S[c]
                c-=1
                S[c]=S[c]~=N
            end
        else if l>=36 then
                if l==37 then
                    N=S[c]
                    c-=1
                    S[c]=Q(S[c],N)
                else c+=1
                    S[c]=X[y]
                    y+=1
                    c+=1
                    S[c]=X[y]
                end
            else N=S[c]
                c-=1
                S[c]=S[c]%N
            end
        end
    end
else if l>=25 then
        if l<27 then
            if l==26 then
                N=S[c]
                c-=1
                local f,k=H(S[c],4294967295),H(N,4294967295)
                local t,z,C,a=H(f,65535),o(f,16),H(k,65535),o(k,16)
                f=H(t*C+G(H(t*a+z*C,65535),16),4294967295)
                t=nil
                repeat k=f%4294967296
                if k~=k then
                    t=0
                    break
                end
                t=k-k%1
            until true
            S[c]=t
        else y=Q(D[y],(H(Q(117,v,E[y]),127)))
        end
    else if l>=28 then
            if l==29 then
                c+=1
                S[c]=S[D[y]]
                y+=1
                N=S[c]
                c-=1
                S[c]=S[c]-N
                y+=1
                c+=1
                S[c]=X[y]
                y+=1
                N=S[c]
                c-=1
                S[c]=S[c]/N
            else N=S[c]
                c-=1
                S[c]=S[c]-N
            end
        else N,g=D[y],Q(s,H(o(s,14),262143),(H(o(s,28),15)))
            R=N<2097152 and 7 or 14
            A,T=o(N,R),H(N,G(1,R)-1)
            E[y]=Q(A,19,(H(o(g,7),127)))
            D[y]=Q(T,20,(H(g,127)))
            y=y-1
        end
    end
else if l>=22 then
        if l>=23 then
            if l==24 then
                c+=1
                S[c]=S[Q(D[y],(H(Q(v,87,E[y]),127)))]
            else S[c-Q(D[y],(H(Q(E[y],y,v),127)))]=S[c]
                c-=1
            end
        else y=if not S[c]then Q(D[y],(H(Q(21,E[y],v),127)))else y
        end
    else if l==21 then
            S[D[y]]=S[c]
            c-=1
            y+=1
            S[D[y]]=S[c]
            c=c-1
        else N,g,R=D[y]+1,Q(D[y+1],(H(Q(w,(H(o(w,29),7))),536870911))),D[y+2]
            for f=1,R,1 do g=H(Q(g,(G(g,13))),536870911)
            g=Q(g,(o(g,13)))
            g=H(Q(g,(G(g,14))),536870911)
            D[N]=Q(D[N],(H(o(g,0),127)))
            E[N]=Q(E[N],(H(o(g,7),127)))
            N=N+1
        end
        E[y]=79
        y=y+2
    end
end
end
end
else if l<10 then
    if l>=5 then
        if l>=7 then
            if l>=8 then
                if l~=9 then
                    N=S[c]
                    c-=1
                    S[c]=S[c]*N
                else y=if S[c]then Q(D[y],(H(v,127)))else y
                end
            else c=c-1
            end
        else if l~=6 then
                N,g=Q(D[y],(H(Q(71,y,v),127))),S[c]
                c-=1
                R=c-N
                A,c=M(S[R](b(S,R+1,c))),R+g-1
                V(A,1,g,R,S)
            else S[c-1]=S[Q(D[y],(H(Q(E[y],16,v),127)))+S[c]]
                c=c-1
            end
        end
    else if l<2 then
            if l~=1 then
                N,g,R=D[y]+1,D[y+1],D[y+2]
                for f=1,R,1 do g=H(Q(g,(G(g,13))),536870911)
                g=Q(g,(o(g,13)))
                g=H(Q(g,(G(g,14))),536870911)
                D[N]=Q(D[N],(H(o(g,0),127)))
                E[N]=Q(E[N],(H(o(g,7),127)))
                N=N+1
            end
            E[y]=79
            y=y+2
        else N=c-1
            g=S[N]
            S[N]=S[c]
            S[c]=g
        end
    else if l>=3 then
            if l~=4 then
                N=S[c]
                c-=1
                S[c]=H(S[c],N)
            else N=S[c]
                c-=1
                S[c]=S[c]+N
            end
        else c+=1
            S[c]=S[D[y]]
            y+=1
            N=D[y]
            g=c-N+1
            V(S,g,c,F+1,S)
            c=F+N
        end
    end
end
else if l>=15 then
    if l<17 then
        if l~=16 then
            c+=1
            S[c]=Q(D[y],(H(y,127)))
        else s=S[c]
            c=c-1
        end
    else if l>=18 then
            if l==19 then
                y,c=if not S[c]then Q(D[y],(H(Q(9,v),127)))else y,c-1
            else N=D[y]
                local f,X,k=o(N,8),H(N,255),Y[4]
                local t=Q(k[f],380445389)
                k[f]=t
                k,f=Y[7],t+1
                t=I(k,f)
                local Y,s
                if t<128 then
                    Y,s=t,f+1
                else local w=I(k,f+1)
                    if w<128 then
                        Y,s=t-128+w*128,f+2
                    else local z=I(k,f+2)
                        if z<128 then
                            Y,s=t-128+(w-128)*16384+z*128,f+3
                        else local C=I(k,f+3)
                            Y,s=(t-128)*2097152+(w-128)*16384+(z-128)+C%128*128+(C-C%128)*2097152,f+4
                        end
                    end
                end
                f,t=X*16843009,s+Y
                local w=t-Y%4
                for Y=s,w-1,4 do P(k,Y,(Q(Z(k,Y),f)))
            end
            for f=w,t-1,1 do h(k,f,(Q(I(k,f),X)))
        end
        D[y]=41
        E[y]=79
    end
else N=D[y]
    g=c-N+1
    V(S,g,c,F+1,S)
    c=F+N
    y+=1
    S[D[y]]=S[c]
    c=c-1
end
end
else if l>=12 then
    if l<13 then
        v=S[c]
        c-=1
        y=Q(D[y],15)+1
        break
    elseif l~=14 then
            if not S[c]then c-=1
            y=Q(D[y],(H(Q(E[y],v,89),127)))
        else N=Q(D[y],(H(Q(y,v,57),127)))
            g=c-N+1
            V(S,g,c,F+1,S)
            c=F+N
        end
    else if l==11 then
            S[Q(D[y],(H(Q(E[y],y),127)))]=S[c]
            c-=1
        else S[c]=#S[c]
        end
    end
end
end
end
end
y=y+1
end
A=g
if v==204 then
    while true do K=D[y]
    if K<3 then
        if K<1 then
            v=S[c]
            c-=1
            y=Q(E[y],(H(Q(D[y],127),127)))+1
            break
        elseif K~=2 then
                y=Q(E[y],(H(Q(86,v,D[y]),127)))
            else c+=1
                S[c]=Q(E[y],(H(Q(72,D[y],y),127)))
            end
        else if K<5 then
                if K~=4 then
                    c+=1
                    S[c]=E[y]
                else N=S[c]
                    y,c=N,c-1
                end
            else if K==6 then
                    N=Q(E[y],(H(Q(D[y],88),127)))
                    if N==0 then
                        return
                    end
                    return b(S,c-N+1,c)
                else c+=1
                    S[c]=nil
                end
            end
        end
        y=y+1
    end
    if v==134 then
        g=A
        while true do T=E[y]
        if T>=3 then
            if T>=5 then
                if T~=6 then
                    N,g,R=D[y]+1,D[y+1],D[y+2]
                    for f=1,R,1 do g=H(Q(g,(G(g,13))),536870911)
                    g=Q(g,(o(g,13)))
                    g=H(Q(g,(G(g,14))),536870911)
                    D[N]=Q(D[N],(H(o(g,0),127)))
                    E[N]=Q(E[N],(H(o(g,7),127)))
                    N=N+1
                end
                E[y]=2
                y=y+2
            else N=S[c]
                y,c=N,c-1
            end
        else if T==4 then
                c+=1
                S[c]=nil
            else N=Q(D[y],(H(Q(y,v,E[y]),127)))
                if N==0 then
                    return
                end
                return b(S,c-N+1,c)
            end
        end
    else if T>=1 then
            y=if T~=2 then
                Q(D[y],(H(E[y],127)))else y
            else c+=1
                S[c]=D[y]
            end
        end
        y=y+1
    end
end
end
end
end

-- Module [53] (25,590 bytes)
Modules[53] =
function(f, X, l, Y, Y_2, D, D_2, E, k, t, g, F, T, K, s, S)
    local S,w,A,N,R,y,c,v,z,C,a,G,Q,H,o,V,M,b,W=f[31],f[29],f[86],f[114],f[37],f[112],f[88],f.QB,f[120],f[12],f[65],f[9],f[77],f[61],f[23],f[105],f.Jt,f[76],f[87]
    return function(I, P, P_2)
        local P,Z,h,j,q,U,e,_,O,p,x,d,i,u,B,m,J,L,r=S,w,A,N,R,y,c,v,z,C,a,G,Q,H,o,V,M,b,W
        return function(...)
            local S,w,A,N,R,y,c
            local v,z,C,a,G,Q,H,o=1628003532
            local V,M=2543780863
            local b,W=k==240,P(t)
            local t,n
            if b then
                t,n=E,k
                while true do local fo=s[t]
                if fo>=62 then
                    if fo<93 then
                        if fo>=77 then
                            if fo>=85 then
                                if fo>=89 then
                                    if fo<91 then
                                        if fo==90 then
                                        y=F[t]
                                        local Xo,lo,Yo=H()
                                        if Xo then
                                        W[y+1]=lo
                                        W[y+2]=Yo
                                        t=D[t]
                                        a,C,Q=Xo,lo,Yo
                                    else W[F[t]]=l[t]*W[D[t]]
                                        end
                                    else if fo==92 then
                                        W[D[t]]=Z(W[F[t]],X[t])
                                    else W[F[t]][l[t]]=D[t]
                                        end
                                        end
                                    else if fo>=87 then
                                        if fo==88 then
                                        W[l[t]]=h(W[F[t]],D[t])
                                    else y=I[l[t]]
                                        W[F[t]]=y[4][y[6]][W[D[t]]]
                                        end
                                    else if fo~=86 then
                                        H,w,G=M[6],M[9],M[8]
                                        M=M[7]
                                    else W[F[t]]=W[D[t]]>=W[l[t]]
                                        end
                                        end
                                    end
                                else if fo<81 then
                                        if fo>=79 then
                                        if fo==80 then
                                        W[F[t]]=W[D[t]][W[l[t]]]
                                    else W[F[t]]=W[D[t]]==X[t]
                                        end
                                    else if fo~=78 then
                                        W[l[t]]=W[F[t]]<W[D[t]]
                                    else y,a,C=l[t],F[t],D[t]
                                        Q,A=y+C-1,y+a
                                        S=W[A]
                                        z=S.n
                                        N=a+z-1
                                        S.n=N
                                        j(S,1,z,a,S)
                                        j(W,y+1,A-1,1,S)
                                        R=q(W[y](U(S,1,S.n)))
                                        j(R,1,C,y,W)
                                        end
                                        end
                                    else if fo<83 then
                                        if fo==82 then
                                        f[X[t]]=g[t]
                                    else y,a,C=l[t],D[t],F[t]
                                        Q,A=W[y],y+a
                                        S=W[A]
                                        j(W,y+1,A-1,C+1,Q)
                                        j(S,1,S.n,C+a,Q)
                                        end
                                    else if fo==84 then
                                        local Xo=F[t]
                                        if c then
                                        local lo=c[Xo]
                                        if lo then
                                        lo[4]=lo
                                        lo[5]=W[Xo]
                                        lo[6]=5
                                        c[Xo]=nil
                                        end
                                        end
                                    else y,a=F[t],W[l[t]]
                                        W[y+1]=a
                                        W[y]=a[T[t]]
                                        end
                                        end
                                    end
                                end
                            else if fo>=69 then
                                    if fo<73 then
                                        if fo>=71 then
                                        if fo==72 then
                                        t=if W[l[t]]~=F[t]then D[t]else t
                                    else y=l[t]
                                        a,C,Q,A=W[y],W[y+1],W[y+2],W[y+3]
                                        W[y]=a(C,Q,A)
                                        end
                                    else if fo==70 then
                                        y=W[l[t]]
                                        W[D[t]]=q(U(y,F[t],y.n))
                                    else W[l[t]]=T[t]+W[F[t]]
                                        end
                                        end
                                    else if fo>=75 then
                                        if fo~=76 then
                                        W[F[t]]=T[t]+X[t]
                                    else W[D[t]]=f
                                        end
                                    elseif fo==74 then
                                        W[l[t]]=not W[F[t]]
                                    else W[F[t]]=W[l[t]]==W[D[t]]
                                        end
                                        end
                                    else if fo<65 then
                                        if fo>=63 then
                                        if fo==64 then
                                        W[l[t]][g[t]]=T[t]
                                    else y,a,C=l[t],D[t],F[t]
                                        Q=y+a
                                        A=W[Q]
                                        S=A.n
                                        z=a+S-1
                                        A.n=z
                                        j(A,1,S,a,A)
                                        j(W,y+1,Q-1,1,A)
                                        W[y]=q(W[y](U(A,1,A.n)))
                                        end
                                    else W[F[t]]=e(X[t],T[t])
                                        end
                                    else if fo<67 then
                                        if fo~=66 then
                                        W[F[t]]=W[l[t]]+T[t]
                                    else W[F[t]]=f[X[t]]
                                        end
                                    else if fo~=68 then
                                        W[l[t]][W[D[t]]]=F[t]
                                    else y,a,C=D[t],l[t],F[t]
                                        Q=y+a
                                        W[y]=q(W[y](U(W,y+1,Q)))
                                        end
                                        end
                                        end
                                    end
                                end
                            else if fo>=109 then
                                    if fo<117 then
                                        if fo<113 then
                                        if fo>=111 then
                                        if fo~=112 then
                                        W[l[t]]=_[T[t]]
                                    else local Xo,lo,Yo=F[t],e(l[t],(h(e(V,(h(O(V,29),7))),536870911))),Y[4]
                                        local Do=e(Yo[Xo],380445389)
                                        Yo[Xo]=Do
                                        Yo,Xo=Y[7],Do+1
                                        Do=p(Yo,Xo)
                                        local Eo,ko
                                        if Do<128 then
                                        Eo,ko=Do,Xo+1
                                    else local to=p(Yo,Xo+1)
                                        if to<128 then
                                        Eo,ko=Do-128+to*128,Xo+2
                                    else local go=p(Yo,Xo+2)
                                        if go<128 then
                                        Eo,ko=Do-128+(to-128)*16384+go*128,Xo+3
                                    else local Fo=p(Yo,Xo+3)
                                        Eo,ko=(Do-128)*2097152+(to-128)*16384+(go-128)+Fo%128*128+(Fo-Fo%128)*2097152,Xo+4
                                        end
                                        end
                                        end
                                        Do,Xo=lo*16843009,ko+Eo
                                        local to=Xo-Eo%4
                                        for Eo=ko,to-1,4 do x(Yo,Eo,(e(d(Yo,Eo),Do)))
                                        end
                                        for Do=to,Xo-1,1 do i(Yo,Do,(e(p(Yo,Do),lo)))
                                    end
                                    F[t]=66
                                    l[t]=48
                                    D[t]=156
                                    s[t]=121
                                end
                            else if fo~=110 then
                                    y=I[F[t]]
                                    y[4][y[6]][W[D[t]]]=W[l[t]]
                                else y=D[t]
                                    a,C,Q=W[y],W[y+1],W[y+2]
                                    W[y]=a(C,Q)
                                end
                            end
                        else if fo>=115 then
                                if fo~=116 then
                                    W[D[t]](W[l[t]],g[t])
                                else W[l[t]]=W[D[t]]*W[F[t]]
                                end
                            elseif fo==114 then
                                    W[F[t]]=Z(W[l[t]],W[D[t]])
                                else W[F[t]]=h(W[l[t]],W[D[t]])
                                end
                            end
                        else if fo>=121 then
                                if fo<123 then
                                    if fo==122 then
                                        a,y=(e(l[t],(h(e(V,(h(O(V,29),7))),536870911)))),F[t]+1
                                        for Xo=1,D[t],1 do a=h(e(a,(u(a,13))),536870911)
                                        a=e(a,(O(a,13)))
                                        a=h(e(a,(u(a,14))),536870911)
                                        F[y]=e(F[y],(h(O(a,0),127)))
                                        l[y]=e(l[y],(h(O(a,7),127)))
                                        D[y]=e(D[y],(h(O(a,14),127)))
                                        s[y]=e(s[y],(h(O(a,21),127)))
                                        y=y+1
                                    end
                                    s[t]=121
                                else if fo==124 then
                                        W[D[t]]=W[l[t]]~=F[t]
                                    else W[l[t]]=W[F[t]]<D[t]
                                    end
                                end
                            else if fo>=119 then
                                    if fo==120 then
                                        t=if W[F[t]]then D[t]else l[t]
                                    else if c then
                                        for Xo in B,c,nil do if c then
                                        local lo=c[Xo]
                                        if lo then
                                        lo[4]=lo
                                        lo[5]=W[Xo]
                                        lo[6]=5
                                        c[Xo]=nil
                                        end
                                        end
                                        end
                                    end
                                    if o then
                                        for Xo,lo in B,o,nil do local Yo=lo[5]
                                        if o then
                                        lo=o[Xo]
                                        if lo then
                                        local Do,Eo=Xo+Yo-1,P(Yo)
                                        j(W,Xo,Do,1,Eo)
                                        lo[4]=Eo
                                        lo[6]=1
                                        o[Xo]=nil
                                        end
                                        end
                                    end
                                end
                                return
                            end
                        else if fo==118 then
                                W[l[t]]=W[D[t]]
                                W[l[t+1]]=W[D[t+1]]
                                t+=1
                            else W[F[t]]=W[l[t]]<=W[D[t]]
                            end
                        end
                    end
                end
            else if fo<101 then
                    if fo<97 then
                        if fo<95 then
                            if fo==94 then
                                W[F[t]][T[t]]=W[l[t]]
                            else a,y=F[t],D[t]+1
                                for Xo=1,l[t],1 do a=h(e(a,(u(a,13))),536870911)
                                a=e(a,(O(a,13)))
                                a=h(e(a,(u(a,14))),536870911)
                                F[y]=e(F[y],(h(O(a,0),127)))
                                l[y]=e(l[y],(h(O(a,7),127)))
                                D[y]=e(D[y],(h(O(a,14),127)))
                                s[y]=e(s[y],(h(O(a,21),127)))
                                y=y+1
                            end
                            s[t]=121
                        end
                    else if fo~=96 then
                            W[D[t]]=W[F[t]]%l[t]
                        else W[l[t]]=g[t]
                        end
                    end
                else if fo>=99 then
                        if fo==100 then
                            W[l[t]]=W[D[t]]()
                        else f[D[t]]=W[F[t]]
                        end
                    else if fo~=98 then
                            local Xo,lo,Yo=D[t],F[t],Y[4]
                            local Do=e(Yo[Xo],380445389)
                            Yo[Xo]=Do
                            Xo,Yo=Y[7],Do+1
                            Do=p(Xo,Yo)
                            local Eo,ko
                            if Do<128 then
                                Eo,ko=Do,Yo+1
                            else local to=p(Xo,Yo+1)
                                if to<128 then
                                    Eo,ko=Do-128+to*128,Yo+2
                                else local go=p(Xo,Yo+2)
                                    if go<128 then
                                        Eo,ko=Do-128+(to-128)*16384+go*128,Yo+3
                                    else local Fo=p(Xo,Yo+3)
                                        Eo,ko=(Do-128)*2097152+(to-128)*16384+(go-128)+Fo%128*128+(Fo-Fo%128)*2097152,Yo+4
                                    end
                                end
                            end
                            Yo,Do=lo*16843009,ko+Eo
                            local to=Do-Eo%4
                            for Eo=ko,to-1,4 do x(Xo,Eo,(e(d(Xo,Eo),Yo)))
                        end
                        for Yo=to,Do-1,1 do i(Xo,Yo,(e(p(Xo,Yo),lo)))
                    end
                    D[t]=11
                    F[t]=215
                    l[t]=246
                    s[t]=121
                else W[l[t]]=W[D[t]]
                    W[D[t+1]]=f[F[t+1]]
                    t+=1
                end
            end
        end
    else if fo<105 then
            if fo>=103 then
                if fo~=104 then
                    local Xo,lo,Yo=F[t],e(l[t],(h(e(v,(h(O(v,29),7))),536870911))),Y[4]
                    local Do=e(Yo[Xo],380445389)
                    Yo[Xo]=Do
                    Yo,Xo=Y[7],Do+1
                    Do=p(Yo,Xo)
                    local Eo,ko
                    if Do<128 then
                        Eo,ko=Do,Xo+1
                    else local to=p(Yo,Xo+1)
                        if to<128 then
                            Eo,ko=Do-128+to*128,Xo+2
                        else local go=p(Yo,Xo+2)
                            if go<128 then
                                Eo,ko=Do-128+(to-128)*16384+go*128,Xo+3
                            else local Fo=p(Yo,Xo+3)
                                Eo,ko=(Do-128)*2097152+(to-128)*16384+(go-128)+Fo%128*128+(Fo-Fo%128)*2097152,Xo+4
                            end
                        end
                    end
                    Xo,Do=lo*16843009,ko+Eo
                    local to=Do-Eo%4
                    for Eo=ko,to-1,4 do x(Yo,Eo,(e(d(Yo,Eo),Xo)))
                end
                for Xo=to,Do-1,1 do i(Yo,Xo,(e(p(Yo,Xo),lo)))
            end
            F[t]=132
            l[t]=41
            D[t]=58
            s[t]=121
        else W[l[t]]=e(W[F[t]],T[t])
        end
    else if fo~=102 then
            t=if F[t]<W[l[t]]then D[t]else t
        else W[F[t]]=D[t]
        end
    end
else if fo>=107 then
        if fo==108 then
            y,a,C=l[t],D[t],F[t]
            Q=W[y]
            j(W,y+1,y+a,C+1,Q)
        else W[F[t]][l[t]]=W[D[t]]
        end
    else if fo~=106 then
            t=W[D[t]]
        else W[D[t]]=W[F[t]][l[t]]
        end
    end
end
end
end
end
else if fo>=31 then
    if fo>=46 then
        if fo>=54 then
            if fo<58 then
                if fo<56 then
                    if fo==55 then
                        W[F[t]]=V
                    else W[l[t]]=W[D[t]]
                        W[l[t+1]](g[t+1],T[t+1])
                        W[F[t+2]]=D[t+2]
                        W[l[t+3]]=W[D[t+3]]
                        W[D[t+4]]()
                        t+=4
                    end
                else if fo==57 then
                        W[D[t]]=_[g[t]][X[t]]
                    else W[l[t]](T[t])
                    end
                end
            else if fo<60 then
                    if fo~=59 then
                        W[D[t]]=W[F[t]]*l[t]
                    else W[l[t]]=#W[F[t]]
                    end
                elseif fo==61 then
                        W[l[t]]=P(F[t])
                    else W[D[t]]=W[F[t]]*X[t]
                    end
                end
            else if fo<50 then
                    if fo>=48 then
                        if fo==49 then
                            M,y,a={[7]=M,[9]=w,[6]=H,[8]=G},F[t],m(J)
                            a(f,W[y],W[y+1],W[y+2])
                            t,H=D[t],a
                        else local m,J,Xo=D[t],W[l[t]],F[t]
                            local lo,Yo=h(J,4294967295),h(Xo,4294967295)
                            local J,Xo,Do,Eo=h(lo,65535),O(lo,16),h(Yo,65535),O(Yo,16)
                            Yo=h(J*Do+u(h(J*Eo+Xo*Do,65535),16),4294967295)
                            Eo=nil
                            repeat lo=Yo%4294967296
                            if lo~=lo then
                                Eo=0
                                break
                            end
                            Eo=lo-lo%1
                        until true
                        W[m]=Eo
                    end
                else local m=t
                    if fo~=47 then
                        W[l[m]]=e(W[F[m]],W[D[m]])
                    else n=D[m]
                        t=l[m]+1
                        break
                    end
                end
            else if fo>=52 then
                    if fo==53 then
                        W[D[t]](W[F[t]],W[l[t]])
                    else y,a,C=l[t],{...},F[t]
                        j(a,1,y-1,C,W)
                        W[C+y-1]=q(L(y,...))
                    end
                else if fo~=51 then
                        local m,J,L=F[t],W[D[t]],W[l[t]]
                        local Xo,lo=h(J,4294967295),h(L,4294967295)
                        local J,Yo,Do,Eo=h(Xo,65535),O(Xo,16),h(lo,65535),O(lo,16)
                        L=h(J*Do+u(h(J*Eo+Yo*Do,65535),16),4294967295)
                        J=nil
                        repeat Eo=L%4294967296
                        if Eo~=Eo then
                            J=0
                            break
                        end
                        J=Eo-Eo%1
                    until true
                    W[m]=J
                else v=W[D[t]]
                end
            end
        end
    end
else if fo>=38 then
        if fo<42 then
            if fo>=40 then
                if fo~=41 then
                    W[l[t]]=W[F[t]](W[D[t]])
                else W[D[t]]=h(W[F[t]],X[t])
                end
            else if fo~=39 then
                    W[l[t]]=D[t]-W[F[t]]
                else y,a,C=l[t],D[t],F[t]
                    Q,A,S=y+C-1,y+a,q(W[y](U(W,y+1,y+a)))
                    j(S,1,C,y,W)
                end
            end
        else if fo>=44 then
                if fo~=45 then
                    W[D[t]]={}
                else W[l[t]]=W[D[t]]<=F[t]
                end
            else if fo==43 then
                    y=I[F[t]]
                    y[4][y[6]][W[D[t]]]=X[t]
                else W[l[t]]=W[D[t]]
                end
            end
        end
    else if fo<34 then
            if fo>=32 then
                if fo==33 then
                    W[l[t]]=W[F[t]]-W[D[t]]
                else W[F[t]]=W[D[t]]~=X[t]
                end
            else t=if W[l[t]]<=F[t]then D[t]else t
            end
        else if fo>=36 then
                if fo==37 then
                    W[l[t]]=W[D[t]][g[t]]
                else W[D[t]]=O(W[l[t]],F[t])
                end
            else if fo~=35 then
                    W[l[t]]=e(W[D[t]],F[t])
                else y,a,C,Q=D[t],F[t],l[t],e(v,h(O(v,14),262143),(h(O(v,28),15)))
                    A=C<16384 and 7 or(C<2097152 and 14 or 21)
                    S,z=h(C,u(1,A)-1),O(C,A)
                    D[t]=e(y,79,(h(O(Q,14),127)))
                    s[t]=e(z,6,(h(O(Q,21),127)))
                    F[t]=e(a,94,(h(Q,127)))
                    l[t]=e(S,121,(h(O(Q,7),127)))
                    t=t-1
                end
            end
        end
    end
end
else if fo<15 then
    if fo>=7 then
        if fo>=11 then
            if fo<13 then
                if fo==12 then
                    W[l[t]](T[t],W[F[t]])
                else y=I[F[t]]
                    y[4][y[6]]=W[D[t]]
                end
            else if fo~=14 then
                    t=if not W[D[t]]then F[t]else l[t]
                else local m,J,L=F[t],W[l[t]]
                    repeat local Xo=J%4294967296
                    if Xo~=Xo then
                        L=0
                        break
                    end
                    L=Xo-Xo%1
                until true
                W[m]=L
            end
        end
    else if fo>=9 then
            if fo==10 then
                W[F[t]]=D[t]
                W[l[t+1]]=g[t+1]
                y,a,C=l[t+2],D[t+2],F[t+2]
                Q,A,S=y+C-1,y+a,q(W[y](U(W,y+1,y+a)))
                j(S,1,C,y,W)
                W[l[t+3]]=W[D[t+3]]
                t=t+3
            else y=I[F[t]]
                W[D[t]]=y[4][y[6]]
            end
        else if fo~=8 then
                W[F[t]][W[l[t]]]=W[D[t]]
            else W[l[t]]=W[D[t]](g[t])
            end
        end
    end
else if fo>=3 then
        if fo>=5 then
            if fo~=6 then
                y=I[D[t]]
                y[4][y[6]]=g[t]
            else t=W[D[t]]
            end
        else if fo==4 then
                W[D[t]]=f[F[t]]
            else a,y=(e(l[t],(h(e(v,(h(O(v,29),7))),536870911)))),F[t]+1
                for m=1,D[t],1 do a=h(e(a,(u(a,13))),536870911)
                a=e(a,(O(a,13)))
                a=h(e(a,(u(a,14))),536870911)
                F[y]=e(F[y],(h(O(a,0),127)))
                l[y]=e(l[y],(h(O(a,7),127)))
                D[y]=e(D[y],(h(O(a,14),127)))
                s[y]=e(s[y],(h(O(a,21),127)))
                y=y+1
            end
            s[t]=121
        end
    end
else if fo<1 then
        V=W[F[t]]
    else if fo==2 then
            y,a,C,Q=l[t],D[t],F[t],e(v,h(O(v,14),262143),(h(O(v,28),15)))
            A=C<2097152 and 7 or 14
            S,z=O(C,A),h(C,u(1,A)-1)
            s[t]=e(S,57,(h(O(Q,21),127)))
            F[t]=e(z,87,(h(Q,127)))
            l[t]=e(y,26,(h(O(Q,7),127)))
            D[t]=e(a,97,(h(O(Q,14),127)))
            t=t-1
        else W[D[t]]=W[l[t]]-g[t]
        end
    end
end
end
else if fo<23 then
    if fo<19 then
        if fo>=17 then
            if fo~=18 then
                W[F[t]]=v
            else W[F[t]]=W[l[t]]-D[t]
            end
        elseif fo==16 then
                W[l[t]][T[t]]=F[t]
            else W[D[t]]=W[F[t]]+W[l[t]]
            end
        else if fo<21 then
                if fo~=20 then
                    t=D[t]
                else local m
                    local J=T[t]
                    if J then
                        local L=#J/3
                        if L>0 then
                            m={}
                            local Xo,lo=c,o
                            for Yo=1,L,1 do local L=(Yo-1)*3
                            local Do,Eo=J[L+3],J[L+2]
                            if Do==1 then
                                Xo=if not Xo then{}else Xo
                                local ko=Xo[Eo]
                                if not ko then
                                    ko={[4]=W,[6]=Eo}
                                    Xo[Eo]=ko
                                    m[Yo]=ko
                                else if Do==3 then
                                        m[Yo]=W[Eo]
                                    else if Do==0 then
                                        m[Yo]=I[Eo]
                                    else if Do==2 then
                                        lo=if not lo then{}else lo
                                        local Do=lo[Eo]
                                        if not Do then
                                        Do={[5]=J[L+1],[6]=Eo,[4]=W}
                                        lo[Eo]=Do
                                        m[Yo]=Do
                                        end
                                        end
                                        end
                                    end
                                    c,o=Xo,lo
                                    W[F[t]]=X[t](m,nil,nil)
                                    y=m
                                end
                            else if fo==22 then
                                    W[F[t]]=W[D[t]]+l[t]
                                else W[l[t]]=W
                                end
                            end
                        end
                    else if fo<27 then
                            if fo<25 then
                                if fo==24 then
                                    t=if W[l[t]]==D[t]then F[t]else t
                                else W[l[t]](g[t],T[t])
                                end
                            else if fo==26 then
                                    W[l[t]](W[F[t]])
                                else W[D[t]]=W[F[t]]==l[t]
                                end
                            end
                        else if fo<29 then
                                if fo==28 then
                                    y,a={...},D[t]
                                    j(y,1,l[t],a,W)
                                else W[D[t]]=W[F[t]]//W[l[t]]
                                end
                            else if fo~=30 then
                                    W[D[t]]()
                                else W[D[t]][W[F[t]]]=X[t]
                                end
                            end
                        end
                    end
                end
            end
        end
        t=t+1
    end
else t,n=E,k
end
if n==46 then
    while true do N=s[t]
    if N>=68 then
        if N<102 then
            if N<85 then
                if N>=76 then
                    if N<80 then
                        if N<78 then
                            t=if N~=77 then
                                if W[D[t]]<l[t]then F[t]else t else W[F[t]]
                            else if N==79 then
                                    t=if W[l[t]]<=F[t]then D[t]else t
                                else w,R,G=D[t],g[t],W[l[t]]
                                    b,H=h(R,4294967295),h(G,4294967295)
                                    local E,k,m,J=h(b,65535),O(b,16),h(H,65535),O(H,16)
                                    M=h(E*m+u(h(E*J+k*m,65535),16),4294967295)
                                    E=nil
                                    repeat m=M%4294967296
                                    if m~=m then
                                        E=0
                                        break
                                    end
                                    E=m-m%1
                                until true
                                W[w]=E
                            end
                        end
                    else if N<82 then
                            if N~=81 then
                                t=if W[l[t]]then F[t]else D[t]
                            else W[F[t]]=W[l[t]]<=D[t]
                            end
                        else if N<83 then
                                if c then
                                    for E in B,c,nil do if c then
                                        local k=c[E]
                                        if k then
                                        k[4]=k
                                        k[5]=W[E]
                                        k[6]=5
                                        c[E]=nil
                                        end
                                    end
                                end
                            end
                            if o then
                                for E,k in B,o,nil do local m=k[5]
                                if o then
                                    k=o[E]
                                    if k then
                                        local J,L=E+m,P(m)
                                        j(W,E,J-1,1,L)
                                        k[4]=L
                                        k[6]=1
                                        o[E]=nil
                                    end
                                end
                            end
                        end
                        return X[t]
                    elseif N~=84 then
                            y,a=F[t],W[D[t]]
                            W[y+1]=a
                            W[y]=a[X[t]]
                        else y=I[l[t]]
                            W[D[t]]=y[4][y[6]]
                        end
                    end
                end
            else if N<72 then
                    if N>=70 then
                        if N~=71 then
                            t=if l[t]<W[F[t]]then D[t]else t
                        else W[F[t]]=e(W[l[t]],D[t])
                        end
                    else if N~=69 then
                            W[l[t]]=f
                        else W[F[t]]=e(W[l[t]],T[t])
                        end
                    end
                else if N<74 then
                        if N~=73 then
                            W[F[t]](W[D[t]],W[l[t]])
                        else W[l[t]]=W[F[t]]+D[t]
                        end
                    else if N==75 then
                            t=if not W[l[t]]then D[t]else F[t]
                        else W[D[t]]={}
                        end
                    end
                end
            end
        else if N<93 then
                if N>=89 then
                    if N>=91 then
                        if N~=92 then
                            t=if W[F[t]]==D[t]then l[t]else t
                        else W[F[t]]=D[t]-W[l[t]]
                        end
                    else if N~=90 then
                            y=I[l[t]]
                            y[4][y[6]][W[F[t]]]=D[t]
                        else W[D[t]]=l[t]%W[F[t]]
                        end
                    end
                else if N>=87 then
                        if N==88 then
                            W[F[t]]=W[l[t]]-D[t]
                        else W[F[t]]=W[l[t]][T[t]]
                        end
                    else if N==86 then
                            W[l[t]]=W[F[t]](U(W[D[t]],1,W[D[t]].n))
                        else W[D[t]]=W[l[t]]
                            W[D[t+1]]=W[l[t+1]]
                            t+=1
                        end
                    end
                end
            else if N>=97 then
                    if N>=99 then
                        if N>=100 then
                            if N~=101 then
                                local E,k,m=F[t],W[D[t]],W[l[t]]
                                local J,L=h(k,4294967295),h(m,4294967295)
                                local fo,Xo,lo,Yo=h(J,65535),O(J,16),h(L,65535),O(L,16)
                                m=h(fo*lo+u(h(fo*Yo+Xo*lo,65535),16),4294967295)
                                k=nil
                                repeat Xo=m%4294967296
                                if Xo~=Xo then
                                    k=0
                                    break
                                end
                                k=Xo-Xo%1
                            until true
                            W[E]=k
                        else W[D[t]]=f[l[t]]
                        end
                    else W[l[t]][D[t]]=W[F[t]]
                    end
                elseif N~=98 then
                        W[D[t]]=W[F[t]]>W[l[t]]
                    else W[l[t]]=F
                    end
                elseif N>=95 then
                        if N~=96 then
                            W[l[t]][W[D[t]]]=W[F[t]]
                        else W[D[t]]=O(W[l[t]],F[t])
                        end
                    elseif N==94 then
                            W[l[t]](T[t],g[t])
                        else W[l[t]](g[t],W[D[t]])
                        end
                    end
                end
            else if N<119 then
                    if N>=110 then
                        if N<114 then
                            if N<112 then
                                if N==111 then
                                    local E,k,m=F[t],W[D[t]],X[t]
                                    local J,L=h(k,4294967295),h(m,4294967295)
                                    local k,m,fo,Xo=h(J,65535),O(J,16),h(L,65535),O(L,16)
                                    J=h(k*fo+u(h(k*Xo+m*fo,65535),16),4294967295)
                                    k=nil
                                    repeat Xo=J%4294967296
                                    if Xo~=Xo then
                                        k=0
                                        break
                                    end
                                    k=Xo-Xo%1
                                until true
                                W[E]=k
                            else local E
                                local k=g[t]
                                if k then
                                    local m=#k/3
                                    if m>0 then
                                        E={}
                                        local J,L=c,o
                                        for fo=1,m,1 do local m=(fo-1)*3
                                        local Xo,lo=k[m+3],k[m+2]
                                        if Xo==1 then
                                        J=if not J then{}else J
                                        local Yo=J[lo]
                                        if not Yo then
                                        Yo={[4]=W,[6]=lo}
                                        J[lo]=Yo
                                        E[fo]=Yo
                                    else if Xo==3 then
                                        E[fo]=W[lo]
                                    else if Xo==0 then
                                        E[fo]=I[lo]
                                    else if Xo==2 then
                                        L=if not L then{}else L
                                        local Xo=L[lo]
                                        if not Xo then
                                        Xo={[5]=k[m+1],[6]=lo,[4]=W}
                                        L[lo]=Xo
                                        E[fo]=Xo
                                        end
                                        end
                                        end
                                        end
                                        c,o=J,L
                                        W[l[t]]=T[t](E,nil,nil)
                                        y=E
                                    end
                                else if N==113 then
                                        W[l[t]]=W[D[t]]>=F[t]
                                    else W[D[t]]=V
                                    end
                                end
                            else if N>=116 then
                                    if N>=117 then
                                        if N~=118 then
                                        W[F[t]]=D
                                    else W[D[t]]=h(W[l[t]],W[F[t]])
                                        end
                                    else W[F[t]]=X[t]+W[D[t]]
                                    end
                                elseif N==115 then
                                        W[D[t]]=W[F[t]]-X[t]
                                    else local E,k,m=l[t],W[F[t]],D[t]
                                        local J,L=h(k,4294967295),h(m,4294967295)
                                        local m,fo,Xo,lo=h(J,65535),O(J,16),h(L,65535),O(L,16)
                                        J=h(m*Xo+u(h(m*lo+fo*Xo,65535),16),4294967295)
                                        m=nil
                                        repeat k=J%4294967296
                                        if k~=k then
                                        m=0
                                        break
                                        end
                                        m=k-k%1
                                    until true
                                    W[E]=m
                                end
                            end
                        else if N>=106 then
                                if N<108 then
                                    if N~=107 then
                                        W[F[t]](T[t])
                                    else y,a,C=l[t],F[t],D[t]
                                        Q=W[y]
                                        j(W,y+1,y+a,C+1,Q)
                                    end
                                else if N==109 then
                                        W[D[t]]=W[F[t]]//l[t]
                                    else W[F[t]]=W[D[t]]==W[l[t]]
                                    end
                                end
                            else if N>=104 then
                                    if N==105 then
                                        W[F[t]]=l
                                    else W[l[t]]=u(W[F[t]],D[t])
                                    end
                                elseif N~=103 then
                                        W[l[t]]=W[D[t]]~=W[F[t]]
                                    else local E=D[t]
                                        if c then
                                        local k=c[E]
                                        if k then
                                        k[4]=k
                                        k[5]=W[E]
                                        k[6]=5
                                        c[E]=nil
                                        end
                                        end
                                    end
                                end
                            end
                        else if N>=127 then
                                if N<131 then
                                    if N>=129 then
                                        if N==130 then
                                        W[D[t]]=W[l[t]]-W[F[t]]
                                    else a,y=(e(F[t],(h(e(V,(h(O(V,29),7))),536870911)))),D[t]+1
                                        for E=1,l[t],1 do a=h(e(a,(u(a,13))),536870911)
                                        a=e(a,(O(a,13)))
                                        a=h(e(a,(u(a,14))),536870911)
                                        D[y]=e(D[y],(h(O(a,0),127)))
                                        F[y]=e(F[y],(h(O(a,7),127)))
                                        l[y]=e(l[y],(h(O(a,14),127)))
                                        s[y]=e(s[y],(h(O(a,21),127)))
                                        y=y+1
                                        end
                                        s[t]=61
                                    end
                                else if N~=128 then
                                        W[D[t]]=e(g[t],X[t])
                                    else y=I[D[t]]
                                        W[F[t]]=y[4][y[6]][X[t]]
                                    end
                                end
                            else if N<133 then
                                    if N~=132 then
                                        y=I[D[t]]
                                        y[4][y[6]][X[t]]=W[F[t]]
                                    else local E,k,m=l[t],T[t],g[t]
                                        local J,L=h(k,4294967295),h(m,4294967295)
                                        local m,fo,Xo,lo=h(J,65535),O(J,16),h(L,65535),O(L,16)
                                        k=h(m*Xo+u(h(m*lo+fo*Xo,65535),16),4294967295)
                                        m=nil
                                        repeat fo=k%4294967296
                                        if fo~=fo then
                                        m=0
                                        break
                                        end
                                        m=fo-fo%1
                                    until true
                                    W[E]=m
                                end
                            else if N>=134 then
                                    if N~=135 then
                                        W[D[t]]=-W[l[t]]
                                    else a,y=F[t],l[t]+1
                                        for E=1,D[t],1 do a=h(e(a,(u(a,13))),536870911)
                                        a=e(a,(O(a,13)))
                                        a=h(e(a,(u(a,14))),536870911)
                                        D[y]=e(D[y],(h(O(a,0),127)))
                                        F[y]=e(F[y],(h(O(a,7),127)))
                                        l[y]=e(l[y],(h(O(a,14),127)))
                                        s[y]=e(s[y],(h(O(a,21),127)))
                                        y=y+1
                                    end
                                    s[t]=61
                                end
                            else W[l[t]]=W[D[t]](g[t])
                            end
                        end
                    end
                else if N>=123 then
                        if N<125 then
                            if N==124 then
                                W[l[t]](W[D[t]],U(W[F[t]],1,W[F[t]].n))
                            else W[D[t]]=s
                            end
                        else if N~=126 then
                                W[F[t]]=#W[D[t]]
                            else y,a,C=D[t],l[t],F[t]
                                Q,A,S=y+C-1,y+a,q(W[y](U(W,y+1,y+a)))
                                j(S,1,C,y,W)
                            end
                        end
                    else if N<121 then
                            if N~=120 then
                                W[D[t]]=e(W[l[t]],W[F[t]])
                            else W[F[t]]=I[l[t]]
                            end
                        else if N~=122 then
                                W[l[t]][g[t]]=W[D[t]]
                            else V=W[D[t]]
                            end
                        end
                    end
                end
            end
        end
    else if N<34 then
            if N<17 then
                if N<8 then
                    if N<4 then
                        if N<2 then
                            if N~=1 then
                                y=I[l[t]]
                                W[D[t]]=y[4][y[6]][W[F[t]]]
                            else W[F[t]]=W[l[t]]%D[t]
                            end
                        else if N~=3 then
                                W[l[t]]=W[F[t]][W[D[t]]]
                            else if c then
                                    for E in B,c,nil do if c then
                                        local k=c[E]
                                        if k then
                                        k[4]=k
                                        k[5]=W[E]
                                        k[6]=5
                                        c[E]=nil
                                        end
                                    end
                                end
                            end
                            if o then
                                for E,k in B,o,nil do local V=k[5]
                                if o then
                                    k=o[E]
                                    if k then
                                        local m=P(V)
                                        j(W,E,E+V-1,1,m)
                                        k[4]=m
                                        k[6]=1
                                        o[E]=nil
                                    end
                                end
                            end
                        end
                        return
                    end
                end
            else if N<6 then
                    if N~=5 then
                        W[l[t]]=Z(g[t],W[D[t]])
                    else y=I[D[t]]
                        y[4][y[6]]=g[t]
                    end
                else if N==7 then
                        W[F[t]]=W[l[t]]>D[t]
                    else y,a,C,Q=l[t],F[t],D[t],e(v,h(O(v,14),262143),(h(O(v,28),15)))
                        A=y<2097152 and 7 or 14
                        S,z=O(y,A),h(y,u(1,A)-1)
                        s[t]=e(S,116,(h(O(Q,21),127)))
                        D[t]=e(C,103,(h(Q,127)))
                        F[t]=e(a,127,(h(O(Q,7),127)))
                        l[t]=e(z,55,(h(O(Q,14),127)))
                        t=t-1
                    end
                end
            end
        else if N>=12 then
                if N>=14 then
                    if N<15 then
                        a,y=(e(F[t],(h(e(v,(h(O(v,29),7))),536870911)))),D[t]+1
                        for E=1,l[t],1 do a=h(e(a,(u(a,13))),536870911)
                        a=e(a,(O(a,13)))
                        a=h(e(a,(u(a,14))),536870911)
                        D[y]=e(D[y],(h(O(a,0),127)))
                        F[y]=e(F[y],(h(O(a,7),127)))
                        l[y]=e(l[y],(h(O(a,14),127)))
                        s[y]=e(s[y],(h(O(a,21),127)))
                        y=y+1
                    end
                    s[t]=61
                else if N==16 then
                        W[l[t]]=W[F[t]][D[t]]
                    else W[D[t]]=l[t]
                    end
                end
            else if N~=13 then
                    W[l[t]][W[F[t]]]=D[t]
                else W[F[t]]=W[l[t]]/D[t]
                end
            end
        else if N<10 then
                if N~=9 then
                    W[F[t]]=D[t]+W[l[t]]
                else W[l[t]]=Z(W[D[t]],g[t])
                end
            else if N==11 then
                    W[D[t]]=v
                else y,a,C,Q=D[t],F[t],e(v,h(O(v,14),262143),(h(O(v,28),15))),l[t]
                    A=y<16384 and 7 or(y<2097152 and 14 or 21)
                    S,z=O(y,A),h(y,u(1,A)-1)
                    s[t]=e(S,103,(h(O(C,21),127)))
                    l[t]=e(Q,116,(h(O(C,14),127)))
                    F[t]=e(a,17,(h(O(C,7),127)))
                    D[t]=e(z,92,(h(C,127)))
                    t=t-1
                end
            end
        end
    end
else if N<25 then
        if N>=21 then
            if N<23 then
                if N~=22 then
                    W[D[t]]=W[F[t]]//W[l[t]]
                else W[F[t]]=h(W[D[t]],X[t])
                end
            elseif N==24 then
                    local E,k,S=D[t],F[t],Y[4]
                    local z=e(S[E],380445389)
                    S[E]=z
                    E,S=Y[7],z+1
                    z=p(E,S)
                    local V,m
                    if z<128 then
                        V,m=z,S+1
                    else local J=p(E,S+1)
                        if J<128 then
                            V,m=z-128+J*128,S+2
                        else local L=p(E,S+2)
                            if L<128 then
                                V,m=z-128+(J-128)*16384+L*128,S+3
                            else local fo=p(E,S+3)
                                V,m=(z-128)*2097152+(J-128)*16384+(L-128)+fo%128*128+(fo-fo%128)*2097152,S+4
                            end
                        end
                    end
                    z,S=k*16843009,m+V
                    local J=S-V%4
                    for V=m,J-1,4 do x(E,V,(e(d(E,V),z)))
                end
                for z=J,S-1,1 do i(E,z,(e(p(E,z),k)))
            end
            D[t]=216
            F[t]=90
            l[t]=81
            s[t]=61
        else W[D[t]]=W[F[t]]>=X[t]
        end
    elseif N>=19 then
            if N==20 then
                W[D[t]]=_[X[t]][g[t]]
            else W[F[t]]=h(W[l[t]],D[t])
            end
        elseif N~=18 then
                W[D[t]]=r(W[F[t]])
            else W[D[t]]=W[l[t]]*F[t]
            end
        else if N>=29 then
                if N<31 then
                    if N~=30 then
                        W[D[t]]=W[l[t]]()
                    else W[F[t]]=f[X[t]]
                    end
                else if N<32 then
                        W[l[t]](W[D[t]],g[t])
                    else if N==33 then
                            W[D[t]]=l[t]
                            W[D[t+1]]=W[l[t+1]]
                            t=t+1
                        else y=F[t]
                            a,C,Q=W[y],W[y+1],W[y+2]
                            W[y]=a(C,Q)
                        end
                    end
                end
            else if N>=27 then
                    if N==28 then
                        W[F[t]]=W[D[t]]<l[t]
                    else W[l[t]]=W[F[t]]+T[t]
                    end
                elseif N==26 then
                        W[F[t]]=not W[D[t]]
                    else W[F[t]]=W[D[t]]==l[t]
                    end
                end
            end
        end
    else if N<51 then
            if N>=42 then
                if N>=46 then
                    if N<48 then
                        if N~=47 then
                            W[D[t]]=W[F[t]]<=W[l[t]]
                        else W[l[t]](W[D[t]])
                        end
                    else if N<49 then
                            for E=l[t],F[t],1 do W[E]=nil
                        end
                    else if N~=50 then
                            W[l[t]]=W[F[t]][D[t]]
                            W[l[t+1]]=W[F[t+1]][D[t+1]]
                            W[l[t+2]]=W[F[t+2]][D[t+2]]
                            W[l[t+3]]=W[D[t+3]]+W[F[t+3]]
                            W[F[t+4]]=W[l[t+4]]<=D[t+4]
                            t+=4
                        else local E,k,S=F[t],l[t],W[D[t]]
                            local z,V=h(k,4294967295),h(S,4294967295)
                            local S,m,J,L=h(z,65535),O(z,16),h(V,65535),O(V,16)
                            k=h(S*J+u(h(S*L+m*J,65535),16),4294967295)
                            S=nil
                            repeat V=k%4294967296
                            if V~=V then
                                S=0
                                break
                            end
                            S=V-V%1
                        until true
                        W[E]=S
                    end
                end
            end
        else if N>=44 then
                if N==45 then
                    W[F[t]]()
                else y=I[l[t]]
                    W[D[t]]=y[4][y[6]]
                    W[l[t+1]](T[t+1],g[t+1])
                    y=I[D[t+2]]
                    y[4][y[6]]=g[t+2]
                    y=I[l[t+3]]
                    W[D[t+3]]=y[4][y[6]]
                    W[F[t+4]]()
                    t=t+4
                end
            else if N~=43 then
                    W[D[t]]=X[t]+g[t]
                else W[l[t]]=Y
                end
            end
        end
    else if N>=38 then
            local E=t
            if N<40 then
                if N~=39 then
                    W[D[E]]=Z(W[F[E]],W[l[E]])
                else n=F[E]
                    t=D[E]+1
                    break
                end
            elseif N~=41 then
                    W[l[E]]=g[E]
                else W[D[E]]=W[l[E]]*g[E]
                end
            else if N<36 then
                    if N==35 then
                        t=l[t]
                    else W[F[t]]=W[l[t]]%T[t]
                    end
                else if N==37 then
                        W[l[t]]=W[D[t]]+W[F[t]]
                    else W[l[t]]=P(F[t])
                    end
                end
            end
        end
    else if N>=59 then
            if N>=63 then
                if N>=65 then
                    if N>=66 then
                        if N~=67 then
                            W[l[t]]=_[T[t]]
                        else W[F[t]]=W[D[t]]/W[l[t]]
                        end
                    else W[l[t]]=W[F[t]]%W[D[t]]
                    end
                elseif N==64 then
                        W[F[t]]=Z(l[t],W[D[t]])
                    else W[l[t]]=D[t]*W[F[t]]
                    end
                else if N<61 then
                        if N~=60 then
                            y=I[l[t]]
                            y[4][y[6]][W[D[t]]]=W[F[t]]
                        else W[D[t]]=W[l[t]]
                        end
                    else if N==62 then
                            W[F[t]]=W[l[t]]*W[D[t]]
                        end
                    end
                end
            else if N<55 then
                    if N<53 then
                        if N==52 then
                            W[F[t]]=e(T[t],W[l[t]])
                        else local E,k,S=F[t],W[l[t]]
                            repeat local z=k%4294967296
                            if z~=z then
                                S=0
                                break
                            end
                            S=z-z%1
                        until true
                        W[E]=S
                    end
                else if N==54 then
                        v=W[l[t]]
                    else y,a,C=D[t],F[t],l[t]
                        Q=y+a
                        W[y]=q(W[y](U(W,y+1,Q)))
                    end
                end
            else if N<57 then
                    if N==56 then
                        y=I[D[t]]
                        y[4][y[6]]=W[F[t]]
                    else W[D[t]]=W[l[t]]~=F[t]
                    end
                else if N==58 then
                        W[D[t]]=W[l[t]]>=W[F[t]]
                    else W[l[t]]=W[F[t]](W[D[t]])
                    end
                end
            end
        end
    end
end
end
t=t+1
end
if n==191 then
    W[F[w]]=X[w]
    W[l[w]]=f[D[w]]
    t=t+1
end
end
eend
end

-- Module [113] (276 bytes)
Modules[113] =
function(f, f_2, f_3, f_4)
    return function(f, X)
        local X=f[1]
        local l=f[2]
        return function()
            local f=1
            while true do local Y=f<=0
            if Y then
                return
            else local Y
                X[4][X[6]]=X[4][X[6]]-X[4][X[6]]%2+1
                local X
                l[4][l[6]],f=(542197*l[4][l[6]]+202482141)%268435456,0
            end
        end
    end
end
end

-- Module [47] (2,432 bytes)
Modules[47] =
function(f, X, l, Y, D, E, E_2, k, t, t_2, g, g_2, F, F_2, T, K, K_2)
    local K,s,S,w,A,N,R,y,c,v,z,C,a=f[31],f[52],f[88],f[12],f[65],f[9],f[77],f[114],f[37],f[76],f[23],f[112],f.bt
    local function G(Q, H, H_2, H_3)
        local H,o,V,M,b,W,I,P,Z,h,j,q,U=K,s,S,w,A,N,R,y,c,v,z,C,a
        local function K(...)
            local s=H
            local S,w,A,N=s(t),k
            local k,t,R,y,c,v,z,C,a=j,P,V,M,b,W,I,Z,h
            local H,V,M,b,W=o(function(...)
                local o,I,P
                while true do local Z=E[w]
                local h=Z>=3
                if h then
                    local h=Z>=4
                    if h then
                        local h=Z==5
                        if h then
                            local h,j,e=l[w],g[w],D[4]
                            local _=R(e[h],380445389)
                            e[h]=_
                            e,h=D[7],_+1
                            _=y(e,h)
                            local D,O
                            if _<128 then
                                D,O=_,h+1
                            else local p=y(e,h+1)
                                if p<128 then
                                    D,O=_-128+p*128,h+2
                                else local x=y(e,h+2)
                                    if x<128 then
                                        D,O=_-128+(p-128)*16384+x*128,h+3
                                    else local d=y(e,h+3)
                                        D,O=(_-128)*2097152+(p-128)*16384+(x-128)+d%128*128+(d-d%128)*2097152,h+4
                                    end
                                end
                            end
                            h,_=j*16843009,O+D
                            local p=_-D%4
                            for D=O,p-1,4 do c(e,D,(R(v(e,D),h)))
                        end
                        for D=p,_-1,1 do z(e,D,(R(y(e,D),j)))
                    end
                    _,j,h=w,w,w
                    l[w]=130
                    g[_]=212
                    T[j]=219
                    E[h]=1
                else local l
                    local D,E,R,y,c=F[w],A,N
                    if D then
                        local F=#D/3
                        if F>0 then
                            l,y,c={},E,R
                            for v=1,F,1 do local F=(v-1)*3
                            local z,h=D[F+3],D[F+2]
                            if z==1 then
                                y=if not y then{}else y
                                local j=y[h]
                                if not j then
                                    j={[4]=S,[6]=h}
                                    y[h]=j
                                    l[v]=j
                                else if z==3 then
                                        l[v]=S[h]
                                    else if z==0 then
                                        l[v]=Q[h]
                                    else if z==2 then
                                        c=if not c then{}else c
                                        local z=c[h]
                                        if not z then
                                        z={[5]=D[F+1],[6]=h,[4]=S}
                                        c[h]=z
                                        l[v]=z
                                        end
                                        end
                                        end
                                    end
                                else y,c=E,R
                                end
                            else y,c=E,R
                            end
                            A,N=y,c
                            S[g[w]]=X[w](l,nil,nil)
                            o=l
                        end
                    else o,I,P=T[w],{...},g[w]
                        t(I,1,o-1,P,S)
                        S[P+o-1]=C(a(o,...))
                    end
                else local X=Z<1
                    if X then
                        local X,l=A,N
                        if X then
                            for D in k,X,nil do if X then
                                local E=X[D]
                                if E then
                                    E[4]=E
                                    E[5]=S[D]
                                    E[6]=5
                                    X[D]=nil
                                end
                            end
                        end
                    end
                    if l then
                        for D,E in k,l,nil do X=E[5]
                        if l then
                            E=l[D]
                            if E then
                                local g,F=D+X,s(X)
                                t(S,D,g-1,1,F)
                                E[4]=F
                                E[6]=1
                                l[D]=nil
                            end
                        end
                    end
                end
                return false,false
            else local X=Z~=2
                if not(X)then S[T[w]]()
            end
        end
    end
    w+=1
end
end,...)
if H then
    if V then
        if M then
            return S[b](q(W,1,W.n))
        else return S[b](q(S,b+1,W))
        end
    elseif b then
            if M then
                return q(b,1,b.n)
            else return q(S,b,W)
            end
        end
    else local X,l,D=A,N,S
        if X then
            for E in k,X,nil do if X then
                local g=X[E]
                if g then
                    g[4]=g
                    g[5]=D[E]
                    g[6]=5
                    X[E]=nil
                end
            end
        end
    end
    if l then
        for E,g in k,l,nil do X=g[5]
        if l then
            g=l[E]
            if g then
                local k,F=E+X,s(X)
                t(D,E,k-1,1,F)
                g[4]=F
                g[6]=1
                l[E]=nil
            end
        end
    end
end
U(f,V,w,Y)
end
end
return K
end
return G
end

-- Module [75] (17,183 bytes)
Modules[75] =
function(f, X, l, Y, D, D_2, E, E_2, k, t, g, g_2, F, F_2, T)
    local K,s,S,w,A,N,R,y,c,v,z,C,a,G,Q,H=f[31],f[52],f[61],f[88],f[86],f[120],f.QB,f[23],f[114],f[37],f[112],f[12],f[65],f[9],f[77],f.bt
    local function o(V, M)
        local M,b,W,I,P,Z,h,j,q,U,e,_,O,p,x,d=K,s,S,w,A,N,R,y,c,v,z,C,a,G,Q,H
        local function K(...)
            local s,S,w=225274242,43221082,M
            local A,N,R,y,c,v=w(F),T,t,g
            local t,g,F,z,C,a,G,Q,H,M,i,u,B=e,j,q,W,I,P,Z,h,U,_,O,p,x
            local W,I,P,Z,h=b(function(...)
                local b,j
                local q,U,e,_,O,p=y==76
                if q then
                    while true do local x=E[R]
                    local m=x>=13
                    if m then
                        local m=x<20
                        if m then
                            local m=x<16
                            if m then
                                local m=x>=14
                                if m then
                                    local m=x~=15
                                    if m then
                                        local m=not A[N]
                                        if m then
                                        N-=1
                                        R=k[R]
                                        end
                                    else local m=not A[N]
                                        if m then
                                        R=k[R]
                                        end
                                        N-=1
                                    end
                                else _=A[N]
                                    N-=1
                                    R=_
                                end
                            else local m=x>=18
                                if m then
                                    local m=x~=19
                                    if m then
                                        _,U,p=k[R]+1,k[R+1],k[R+2]
                                        for m=1,p,1 do U=a(C(U,(z(U,13))),536870911)
                                        U=C(U,(G(U,13)))
                                        U=a(C(U,(z(U,14))),536870911)
                                        k[_]=C(k[_],(a(G(U,0),127)))
                                        E[_]=C(E[_],(a(G(U,7),127)))
                                        _=_+1
                                    end
                                    E[R]=9
                                    R+=2
                                else N+=1
                                    local m=N
                                    A[m]=Q[l[R]]
                                    R+=1
                                    N+=1
                                    m=N
                                    A[m]=V[k[R]]
                                    R+=1
                                    _=A[N]
                                    N-=1
                                    m=N
                                    A[m]=A[m]~=_
                                end
                            else local m=x==17
                                if m then
                                    local m,J=c,v
                                    if m then
                                        for L in g,m,nil do if m then
                                        local r=m[L]
                                        if r then
                                        R4=r
                                        R5=A[L]
                                        R6=5
                                        m[L]=nil
                                        end
                                        end
                                    end
                                end
                                if J then
                                    for L,r in g,J,nil do m=R5
                                    if J then
                                        r=J[L]
                                        if r then
                                        local n=w(m)
                                        F(A,L,L+m-1,1,n)
                                        R4=n
                                        R6=1
                                        J[L]=nil
                                        end
                                    end
                                end
                            end
                            _=k[R]
                            if _==0 then
                                return false,false
                            end
                            U=N-_+1
                            m=N
                            return false,false,U,m
                        else _,U,p=k[R]+1,C(k[R+1],(a(C(S,(a(G(S,29),7))),536870911))),k[R+2]
                            for m=1,p,1 do U=a(C(U,(z(U,13))),536870911)
                            U=C(U,(G(U,13)))
                            U=a(C(U,(z(U,14))),536870911)
                            k[_]=C(k[_],(a(G(U,0),127)))
                            E[_]=C(E[_],(a(G(U,7),127)))
                            _=_+1
                        end
                        E[R]=9
                        R+=2
                    end
                end
            end
        else local m=x>=23
            if m then
                local m=x>=25
                if m then
                    local m=x~=26
                    if m then
                        local m=not A[N]
                        if m then
                            R=k[R]
                        end
                    else _=N-1
                        U=A[_]
                        A[_]=A[N]
                        A[N]=U
                    end
                else local m=x~=24
                    if m then
                        _=A[N]
                        N-=1
                        local m=N
                        A[m]=A[m]==_
                    else N+=1
                        local m=N
                        A[m]=k[R]
                        R+=1
                        _,U=k[R],A[N]
                        N-=1
                        p=N-_
                        _,N=H(A[p](t(A,p+1,N))),p+U-1
                        F(_,1,U,p,A)
                    end
                end
            else local m=x>=21
                if m then
                    local m=x==22
                    if m then
                        N+=1
                        local m=N
                        A[m]=V[k[R]]
                        R+=1
                        N+=1
                        m=N
                        A[m]=V[k[R]]
                        R+=1
                        N+=1
                        m=N
                        A[m]=k[R]
                        R+=1
                        _,U=k[R],A[N]
                        N-=1
                        p=N-_
                        _,N=H(A[p](t(A,p+1,N))),p+U-1
                        F(_,1,U,p,A)
                    else s=A[N]
                        N-=1
                    end
                else N+=1
                    local m=N
                    A[m]=V[k[R]]
                end
            end
        end
    else local m=x<6
        if m then
            local m=x>=3
            if m then
                local m=x<4
                if m then
                    _,U=V[k[R]],A[N]
                    N-=1
                    _[4][_[6]]=U
                else local m=x==5
                    if m then
                        _={...}
                        F(_,1,k[R],1,A)
                    else R=k[R]
                    end
                end
            else local m=x<1
                if m then
                    S=A[N]
                    N-=1
                else local m=x~=2
                    if m then
                        _=V[k[R]]
                        N+=1
                        local m=N
                        A[m]=_[4][_[6]]
                    else _=A[N]
                        N-=1
                        local m=N
                        A[m]=A[m]~=_
                    end
                end
            end
        else local m=x>=9
            if m then
                local m=x<11
                if m then
                    local m=x==10
                    if m then
                        N+=1
                        local m=N
                        A[m]=k[R]
                    end
                else local m=x~=12
                    if m then
                        _,U=C(S,a(G(S,14),262143),(a(G(S,28),15))),k[R]
                        p=U<16384 and 7 or(U<2097152 and 14 or 21)
                        e,O=a(U,z(1,p)-1),G(U,p)
                        local m=R
                        k[m]=C(e,60,(a(_,127)))
                        m=R
                        E[m]=C(O,67,(a(G(_,7),127)))
                        R-=1
                    else N+=1
                        local m=N
                        A[m]=l[R]
                    end
                end
            else local m=x<7
                if m then
                    y=A[N]
                    N-=1
                    R=k[R]+1
                    break
                else local m=x==8
                    if m then
                        local x=not A[N]
                        if x then
                            R=k[R]
                        else N-=1
                        end
                    else _,U,p=k[R]+1,C(k[R+1],(a(C(s,(a(G(s,29),7))),536870911))),k[R+2]
                        for x=1,p,1 do U=a(C(U,(z(U,13))),536870911)
                        U=C(U,(G(U,13)))
                        U=a(C(U,(z(U,14))),536870911)
                        k[_]=C(k[_],(a(G(U,0),127)))
                        E[_]=C(E[_],(a(G(U,7),127)))
                        _=_+1
                    end
                    E[R]=9
                    R+=2
                end
            end
        end
    end
end
R+=1
end
q=y==10
if q then
    while true do local x=k[R]
    local m=x>=19
    if m then
        local m=x<29
        if m then
            local m=x>=24
            if m then
                local m=x>=26
                if m then
                    local m=x>=27
                    if m then
                        local m=x==28
                        if m then
                            _=A[N]
                            N-=1
                            local m=N
                            A[m]=A[m][_]
                        else local m,J=c,E[R]
                            if m then
                                local L=m[J]
                                if L then
                                    L[4]=L
                                    L[5]=A[J]
                                    L[6]=5
                                    m[J]=nil
                                end
                            end
                        end
                    else _=A[N]
                        N-=1
                        local m=N
                        A[m]=A[m]==_
                    end
                else local m=x~=25
                    if m then
                        N+=1
                        local m=N
                        A[m]=E[R]
                    else _,U,p=E[R]+1,C(E[R+1],(a(C(s,(a(G(s,29),7))),536870911))),E[R+2]
                        for m=1,p,1 do U=a(C(U,(z(U,13))),536870911)
                        U=C(U,(G(U,13)))
                        U=a(C(U,(z(U,14))),536870911)
                        E[_]=C(E[_],(a(G(U,0),127)))
                        k[_]=C(k[_],(a(G(U,7),127)))
                        _=_+1
                    end
                    k[R]=23
                    R+=2
                end
            end
        else local m=x<21
            if m then
                local m=x==20
                if m then
                    N+=1
                    local m=N
                    A[m]=Q[X[R]]
                else local m
                    local J,L,r,n,fo=X[R],c,v
                    if J then
                        local Xo=#J/3
                        if Xo>0 then
                            m,n,fo={},L,r
                            for lo=1,Xo,1 do local Xo=(lo-1)*3
                            local Yo,Do=J[Xo+3],J[Xo+2]
                            if Yo==1 then
                                n=if not n then{}else n
                                local Eo=n[Do]
                                if not Eo then
                                    Eo={[4]=A,[6]=Do}
                                    n[Do]=Eo
                                    m[lo]=Eo
                                else if Yo==3 then
                                        m[lo]=A[Do]
                                    else if Yo==0 then
                                        m[lo]=V[Do]
                                    else if Yo==2 then
                                        fo=if not fo then{}else fo
                                        local Yo=fo[Do]
                                        if not Yo then
                                        Yo={[5]=J[Xo+1],[6]=Do,[4]=A}
                                        fo[Do]=Yo
                                        m[lo]=Yo
                                        end
                                        end
                                        end
                                    end
                                else n,fo=L,r
                                end
                            else n,fo=L,r
                            end
                            c,v=n,fo
                            r=N
                            A[r]=A[r](m,nil,nil)
                            _=m
                        end
                    else local m=x>=22
                        if m then
                            local m=x==23
                            if m then
                            else local m=N
                                _=A[m-E[R]]
                                N+=1
                                A[N]=_
                            end
                        else _,U,p=E[R]+1,C(E[R+1],(a(C(S,(a(G(S,29),7))),536870911))),E[R+2]
                            for m=1,p,1 do U=a(C(U,(z(U,13))),536870911)
                            U=C(U,(G(U,13)))
                            U=a(C(U,(z(U,14))),536870911)
                            E[_]=C(E[_],(a(G(U,0),127)))
                            k[_]=C(k[_],(a(G(U,7),127)))
                            _=_+1
                        end
                        k[R]=23
                        R+=2
                    end
                end
            end
        else local m=x>=34
            if m then
                local m=x<36
                if m then
                    local m=x==35
                    if m then
                        N+=1
                        local m=N
                        A[m]=Q[X[R]]
                        R+=1
                        N+=1
                        m=N
                        A[m]=V[E[R]]
                    else _,U,p,e=A[N]+0,A[N-1]+0,A[N-2]+0,N-2
                        A[e]=p-_
                        A[e+1]=U
                        A[e+2]=_
                        A[e+3]=E[R]
                        A[e+4]=false
                        N=e+4
                    end
                else local m=x<37
                    if m then
                        N+=1
                        local m=N
                        A[m]=X[R]
                    else local m=x==38
                        if m then
                            _=E[R]
                            local m,J,L=G(_,8),a(_,255),Y[4]
                            local r=C(L[m],380445389)
                            L[m]=r
                            L,m=Y[7],r+1
                            r=M(L,m)
                            local n,fo
                            if r<128 then
                                n,fo=r,m+1
                            else local Xo=M(L,m+1)
                                if Xo<128 then
                                    n,fo=r-128+Xo*128,m+2
                                else local lo=M(L,m+2)
                                    if lo<128 then
                                        n,fo=r-128+(Xo-128)*16384+lo*128,m+3
                                    else local Yo=M(L,m+3)
                                        n,fo=(r-128)*2097152+(Xo-128)*16384+(lo-128)+Yo%128*128+(Yo-Yo%128)*2097152,m+4
                                    end
                                end
                            end
                            m,r=J*16843009,fo+n
                            local Xo=r-n%4
                            for n=fo,Xo-1,4 do i(L,n,(C(u(L,n),m)))
                        end
                        for m=Xo,r-1,1 do B(L,m,(C(M(L,m),J)))
                    end
                    fo=R
                    E[fo],k[fo]=45,23
                else N+=1
                    local m=N
                    A[m]=E[R]
                    R+=1
                    _,U=E[R],A[N]
                    N-=1
                    p=N-_
                    _,N=H(A[p](t(A,p+1,N))),p+U-1
                    F(_,1,U,p,A)
                end
            end
        end
    else local m=x>=31
        if m then
            local m=x<32
            if m then
                N+=1
                local m=N
                A[m]=E[R]
                R+=1
                _,U=E[R],A[N]
                N-=1
                p=N-_
                _,N=H(A[p](t(A,p+1,N))),p+U-1
                F(_,1,U,p,A)
                R+=1
                N+=1
                m=N
                A[m]=X[R]
                R+=1
                _=A[N]
                N-=1
                m=N
                A[m]=A[m]~=_
            else local m=x==33
                if m then
                    local m=N
                    N=m-E[R]
                else local m=not A[N]
                    if m then
                        R=E[R]
                    end
                end
            end
        else local m=x==30
            if m then
                local m,J=c,v
                if m then
                    for L in g,m,nil do if m then
                        local r=m[L]
                        if r then
                            R4=r
                            R5=A[L]
                            R6=5
                            m[L]=nil
                        end
                    end
                end
            end
            if J then
                for L,r in g,J,nil do m=R5
                if J then
                    r=J[L]
                    if r then
                        local n=w(m)
                        F(A,L,L+m-1,1,n)
                        R4=n
                        R6=1
                        J[L]=nil
                    end
                end
            end
        end
        _=E[R]
        if _==0 then
            return false,false
        end
        U=N-_+1
        J=N
        return false,false,U,J
    else local m=N
        A[m]=not A[m]
    end
end
end
end
else local m=x<9
if m then
    local m=x>=4
    if m then
        local m=x>=6
        if m then
            local m=x<7
            if m then
                _=N-1
                U=A[_]
                A[_]=A[N]
                A[N]=U
            else local m=x~=8
                if m then
                    _,U=V[E[R]],A[N]
                    N-=1
                    _[4][_[6]]=U
                else A[E[R]]=A[N]
                    N-=1
                end
            end
        else local m=x==5
            if m then
                N+=1
                local m=N
                A[m]=X[R]
                R+=1
                N+=1
                m=N
                A[m]=X[R]
            else N+=1
                A[N]={}
            end
        end
    else local m=x>=2
        if m then
            local m=x==3
            if m then
                N+=1
                local m=N
                A[m]=V[E[R]]
            else y=A[N]
                N-=1
                R=E[R]+1
                break
            end
        else local m=x~=1
            if m then
                local m=not A[N]
                if m then
                    R=E[R]
                end
                N-=1
            else R=E[R]
            end
        end
    end
else local m=x>=14
    if m then
        local m=x<16
        if m then
            local m=x~=15
            if m then
                _=A[N]
                N-=1
                local m=N
                A[m]=A[m]~=_
            else local m=not A[N]
                if m then
                    N-=1
                    R=E[R]
                end
            end
        else local m=x<17
            if m then
                N+=1
                local m=N
                A[m]=V[E[R]]
                R+=1
                N+=1
                m=N
                A[m]=E[R]
                R+=1
                _,U=E[R],A[N]
                N-=1
                p=N-_
                _,N=H(A[p](t(A,p+1,N))),p+U-1
                F(_,1,U,p,A)
                R+=1
                N+=1
                m=N
                A[m]=X[R]
            else local X=x~=18
                if X then
                    _=A[N]
                    N-=1
                    R=_
                else _,U,p,e,O=A[N-4],A[N-3],A[N-2],A[N-1],A[N]
                    j=_+p
                    b=if p<=0 then
                        j>=U else j<=U
                        if b then
                            A[N-4]=j
                            A[N]=true
                            local X=e~=0
                            if X then
                                A[e]=j
                            else N+=1
                                A[N]=j
                            end
                            R=E[R]
                        else N-=5
                        end
                    end
                end
            end
        else local X=x<11
            if X then
                local X=x~=10
                if X then
                    _,U=C(S,a(G(S,14),262143),(a(G(S,28),15))),E[R]
                    p=U<16384 and 7 or(U<2097152 and 14 or 21)
                    e,O=a(U,z(1,p)-1),G(U,p)
                    local X=R
                    k[X]=C(O,42,(a(G(_,7),127)))
                    X=R
                    E[X]=C(e,12,(a(_,127)))
                    R-=1
                else _,U=E[R],A[N]
                    N-=1
                    p=N-_
                    e,N=H(A[p](t(A,p+1,N))),p+U-1
                    F(e,1,U,p,A)
                end
            else local X=x>=12
                if X then
                    local X=x~=13
                    if X then
                        _,U,p=A[N],A[N-1],A[N-2]
                        N-=3
                        p[U]=_
                    else N+=1
                        local X=N
                        A[X]=A[E[R]]
                    end
                else _,U,p=E[R]+1,E[R+1],E[R+2]
                    for X=1,p,1 do U=a(C(U,(z(U,13))),536870911)
                    U=C(U,(G(U,13)))
                    U=a(C(U,(z(U,14))),536870911)
                    E[_]=C(E[_],(a(G(U,0),127)))
                    k[_]=C(k[_],(a(G(U,7),127)))
                    _=_+1
                end
                k[R]=23
                R+=2
            end
        end
    end
end
end
R+=1
end
q=y==120
if q then
    while true do b=E[R]
    j=b<20
    if j then
        local X=b<10
        if X then
            local X=b<5
            if X then
                local X=b>=2
                if X then
                    local X=b>=3
                    if X then
                        local X=b~=4
                        if X then
                            _=N-1
                            U=A[_]
                            A[_]=A[N]
                            A[N]=U
                        else N+=1
                            local X=N
                            A[X]=V[k[R]]
                            R+=1
                            N+=1
                            X=N
                            A[X]=V[k[R]]
                        end
                    else local X=b==1
                        if X then
                            local X=N
                            _=A[X-k[R]]
                            N+=1
                            A[N]=_
                            R+=1
                            X=N
                            _=A[X-k[R]]
                            N+=1
                            A[N]=_
                        else _=A[N]
                            N-=1
                            local X=N
                            A[X]=A[X]==_
                        end
                    end
                else local X=b>=7
                    if X then
                        local X=b>=8
                        if X then
                            local X=b==9
                            if X then
                                local X=not A[N]
                                if X then
                                    R=k[R]
                                else N-=1
                                end
                            else N+=1
                                local X=N
                                A[X]=V[k[R]]
                                R+=1
                                X=N
                                _=A[X-k[R]]
                                N+=1
                                A[N]=_
                                R+=1
                                N+=1
                                X=N
                                A[X]=k[R]
                                R+=1
                                _,U=k[R],A[N]
                                N-=1
                                p=N-_
                                _,N=H(A[p](t(A,p+1,N))),p+U-1
                                F(_,1,U,p,A)
                            end
                        else _=k[R]
                            U=N-_+1
                            F(A,U,N,T+1,A)
                            N=T+_
                        end
                    else local X=b==6
                        if X then
                            local X=N
                            A[X]=not A[X]
                        else _,N=A[N],T+1
                            A[T+1]=_
                        end
                    end
                end
            else local X=b>=15
                if X then
                    local X=b<17
                    if X then
                        local X=b~=16
                        if X then
                            local X=not A[N]
                            if X then
                                R=k[R]
                            end
                        else local X,x=c,v
                            if X then
                                for m in g,X,nil do if X then
                                    local J=X[m]
                                    if J then
                                        J[4]=J
                                        J[5]=A[m]
                                        J[6]=5
                                        X[m]=nil
                                    end
                                end
                            end
                        end
                        if x then
                            for m,J in g,x,nil do X=J[5]
                            if x then
                                J=x[m]
                                if J then
                                    local L=w(X)
                                    F(A,m,m+X-1,1,L)
                                    J[4]=L
                                    J[6]=1
                                    x[m]=nil
                                end
                            end
                        end
                    end
                    _=k[R]
                    if _==0 then
                        return false,false
                    end
                    U=N-_+1
                    X=N
                    return false,false,U,X
                end
            else local X=b>=18
                if X then
                    local X=b~=19
                    if X then
                        N+=1
                        local X=N
                        A[X]=l[R]
                        R+=1
                        _=A[N]
                        N-=1
                        X=N
                        A[X]=A[X]~=_
                    else _,U,p=k[R]+1,k[R+1],k[R+2]
                        for X=1,p,1 do U=a(C(U,(z(U,13))),536870911)
                        U=C(U,(G(U,13)))
                        U=a(C(U,(z(U,14))),536870911)
                        k[_]=C(k[_],(a(G(U,0),127)))
                        E[_]=C(E[_],(a(G(U,7),127)))
                        _=_+1
                    end
                    E[R]=4
                    R+=2
                end
            else N+=1
                local X=N
                A[X]=k[R]
                R+=1
                _,U=k[R],A[N]
                N-=1
                p=N-_
                _,N=H(A[p](t(A,p+1,N))),p+U-1
                F(_,1,U,p,A)
            end
        end
    else local X=b>=12
        if X then
            local X=b<13
            if X then
                local X=N
                N=X-k[R]
            else local X=b==14
                if X then
                    y=A[N]
                    N-=1
                    R=k[R]+1
                    break
                else N+=1
                    local X=N
                    A[X]=V[k[R]]
                end
            end
        else local X=b==11
            if X then
                local X=N
                _=A[X-k[R]]
                N+=1
                A[N]=_
            else _=A[N]
                N-=1
                A[N]+=_
            end
        end
    end
end
else local X=b<30
if X then
    local X=b>=25
    if X then
        local X=b>=27
        if X then
            local X=b>=28
            if X then
                local X=b==29
                if X then
                    _,U,p=k[R]+1,C(k[R+1],(a(C(S,(a(G(S,29),7))),536870911))),k[R+2]
                    for X=1,p,1 do U=a(C(U,(z(U,13))),536870911)
                    U=C(U,(G(U,13)))
                    U=a(C(U,(z(U,14))),536870911)
                    k[_]=C(k[_],(a(G(U,0),127)))
                    E[_]=C(E[_],(a(G(U,7),127)))
                    _=_+1
                end
                E[R]=4
                R+=2
            else N+=1
                local X=N
                A[X]=Q[l[R]]
            end
        else _,U,p=N-1,N-2,A[N]
            e,O=A[_],A[U]
            A[N]=O
            A[_]=p
            A[U]=e
        end
    else local X=b~=26
        if X then
            _,U=V[k[R]],A[N]
            N-=1
            _[4][_[6]]=U
        else _,U=C(s,a(G(s,14),262143),(a(G(s,28),15))),k[R]
            p=U<16384 and 7 or(U<2097152 and 14 or 21)
            e,O=G(U,p),a(U,z(1,p)-1)
            local X=R
            E[X]=C(e,57,(a(G(_,7),127)))
            X=R
            k[X]=C(O,28,(a(_,127)))
            R-=1
        end
    end
else local X=b<22
    if X then
        local X=b==21
        if X then
            N+=1
            local X=N
            A[X]=k[R]
        else N+=1
            local X=N
            A[X]=A[k[R]]
        end
    else local X=b>=23
        if X then
            local X=b~=24
            if X then
                _=k[R]
                local X,Q,x=G(_,8),a(_,255),Y[4]
                local m=C(x[X],380445389)
                x[X]=m
                x,X=Y[7],m+1
                m=M(x,X)
                local Y,J
                if m<128 then
                    Y,J=m,X+1
                else local L=M(x,X+1)
                    if L<128 then
                        Y,J=m-128+L*128,X+2
                    else local r=M(x,X+2)
                        if r<128 then
                            Y,J=m-128+(L-128)*16384+r*128,X+3
                        else local n=M(x,X+3)
                            Y,J=(m-128)*2097152+(L-128)*16384+(r-128)+n%128*128+(n-n%128)*2097152,X+4
                        end
                    end
                end
                m,X=Q*16843009,J+Y
                local L=X-Y%4
                for Y=J,L-1,4 do i(x,Y,(C(u(x,Y),m)))
            end
            for Y=L,X-1,1 do B(x,Y,(C(M(x,Y),Q)))
        end
        Q=R
        k[Q],E[Q]=29,4
    else N+=1
        local X=N
        A[X]=l[R]
    end
else local X=not A[N]
    if X then
        N-=1
        R=k[R]
    end
end
end
end
else local X=b<35
if X then
    local X=b>=32
    if X then
        local X=b>=33
        if X then
            local X=b~=34
            if X then
                local X=not A[N]
                if X then
                    R=k[R]
                end
                N-=1
            else local X,Y,Q=N,A[N]
                repeat local M=Y%4294967296
                if M~=M then
                    Q=0
                    break
                end
                Q=M-M%1
            until true
            A[X]=Q
        end
    else _=A[N]
        N-=1
        local X=N
        A[X]=C(A[X],_)
    end
else local X=b==31
    if X then
        S=A[N]
        N-=1
    else _,U,p=k[R]+1,C(k[R+1],(a(C(s,(a(G(s,29),7))),536870911))),k[R+2]
        for X=1,p,1 do U=a(C(U,(z(U,13))),536870911)
        U=C(U,(G(U,13)))
        U=a(C(U,(z(U,14))),536870911)
        k[_]=C(k[_],(a(G(U,0),127)))
        E[_]=C(E[_],(a(G(U,7),127)))
        _=_+1
    end
    E[R]=4
    R+=2
end
end
else local X=b>=37
if X then
    local X=b>=38
    if X then
        local X=b~=39
        if X then
            local X=N
            A[X-k[R]]=A[N]
            N-=1
        else N+=1
            A[N]=S
        end
    else R=k[R]
    end
else local X=b~=36
    if X then
        _=A[N]
        N-=1
        R=_
    else local X
        local Y,Q,M,x,i=l[R],c,v
        if Y then
            local u=#Y/3
            if u>0 then
                X,x,i={},Q,M
                for B=1,u,1 do local u=(B-1)*3
                local m,J=Y[u+3],Y[u+2]
                if m==1 then
                    x=if not x then{}else x
                    local L=x[J]
                    if not L then
                        L={[4]=A,[6]=J}
                        x[J]=L
                        X[B]=L
                    else if m==3 then
                            X[B]=A[J]
                        else if m==0 then
                                X[B]=V[J]
                            else if m==2 then
                                    i=if not i then{}else i
                                    local m=i[J]
                                    if not m then
                                        m={[5]=Y[u+1],[6]=J,[4]=A}
                                        i[J]=m
                                        X[B]=m
                                    end
                                end
                            end
                        end
                    else x,i=Q,M
                    end
                else x,i=Q,M
                end
                c,v=x,i
                x=N
                A[x]=A[x](X,nil,nil)
                _=X
            end
        end
    end
end
end
R+=1
end
j=y==215
if j then
    while true do q=E[R]
    b=q<15
    if b then
        local X=q>=7
        if X then
            local X=q>=11
            if X then
                local X=q<13
                if X then
                    local X=q==12
                    if X then
                        _,U,p=k[R]+1,k[R+1],k[R+2]
                        for X=1,p,1 do U=a(C(U,(z(U,13))),536870911)
                        U=C(U,(G(U,13)))
                        U=a(C(U,(z(U,14))),536870911)
                        k[_]=C(k[_],(a(G(U,0),127)))
                        E[_]=C(E[_],(a(G(U,7),127)))
                        _=_+1
                    end
                    E[R]=3
                    R+=2
                else _,U=C(s,a(G(s,14),262143),(a(G(s,28),15))),k[R]
                    p=U<16384 and 7 or(U<2097152 and 14 or 21)
                    e,O=G(U,p),a(U,z(1,p)-1)
                    local X=R
                    E[X]=C(e,12,(a(G(_,7),127)))
                    X=R
                    k[X]=C(O,1,(a(_,127)))
                    R-=1
                end
            else local X=q==14
                if X then
                    N+=1
                    local X=N
                    A[X]=k[R]
                else _=A[N]
                    N-=1
                    local X=N
                    A[X]=C(A[X],_)
                end
            end
        else local X=q>=9
            if X then
                local X=q==10
                if X then
                    local X,Y=c,v
                    if X then
                        for y in g,X,nil do if X then
                            local Q=X[y]
                            if Q then
                                Q[4]=Q
                                Q[5]=A[y]
                                Q[6]=5
                                X[y]=nil
                            end
                        end
                    end
                end
                if Y then
                    for y,Q in g,Y,nil do X=Q[5]
                    if Y then
                        Q=Y[y]
                        if Q then
                            local M=w(X)
                            F(A,y,y+X-1,1,M)
                            Q[4]=M
                            Q[6]=1
                            Y[y]=nil
                        end
                    end
                end
            end
            _=A[N]
            N-=1
            U=N-_
            Y=N
            return true,false,U,Y
        else R=k[R]
        end
    else local X=q~=8
        if X then
            local X=not A[N]
            if X then
                R=k[R]
            else N-=1
            end
        else _=A[N]
            N+=1
            A[N]=_
            R+=1
            N+=1
            local X=N
            A[X]=l[R]
            R+=1
            _=A[N]
            N-=1
            X=N
            A[X]=A[X]~=_
        end
    end
end
else local X=q>=3
if X then
    local X=q>=5
    if X then
        local X=q==6
        if X then
            _=A[N]
            N-=1
            local X=N
            A[X]=A[X]==_
        else _=A[N]
            N-=1
            R=_
        end
    else local X=q==4
        if X then
            local X=N
            A[X]=not A[X]
        end
    end
else local X=q<1
    if X then
        _,N=A[N],T+1
        A[T+1]=_
    else local X=q~=2
        if X then
            _,U,p=k[R]+1,C(k[R+1],(a(C(S,(a(G(S,29),7))),536870911))),k[R+2]
            for X=1,p,1 do U=a(C(U,(z(U,13))),536870911)
            U=C(U,(G(U,13)))
            U=a(C(U,(z(U,14))),536870911)
            k[_]=C(k[_],(a(G(U,0),127)))
            E[_]=C(E[_],(a(G(U,7),127)))
            _=_+1
        end
        E[R]=3
        R+=2
    else N+=1
        local X=N
        A[X]=l[R]
    end
end
end
end
else local X=q>=22
if X then
    local X=q>=26
    if X then
        local X=q>=28
        if X then
            local X=q~=29
            if X then
                _=A[N]
                N-=1
                local X=N
                A[X]=A[X]~=_
            else N+=1
                local X=N
                A[X]=A[k[R]]
            end
        else local X=q~=27
            if X then
                N+=1
                local X=N
                A[X]=l[R]
                R+=1
                _,U=V[k[R]],A[N]
                N-=1
                _[4][_[6]]=U
            else _=V[k[R]]
                N+=1
                local X=N
                A[X]=_[4][_[6]]
            end
        end
    else local X=q<24
        if X then
            local X=q~=23
            if X then
                local X=N
                _=A[X-k[R]]
                N+=1
                A[N]=_
            else N+=1
                local X=N
                A[X]=V[k[R]]
            end
        else local X=q~=25
            if X then
                N-=1
            else _,U,p=k[R]+1,C(k[R+1],(a(C(s,(a(G(s,29),7))),536870911))),k[R+2]
                for X=1,p,1 do U=a(C(U,(z(U,13))),536870911)
                U=C(U,(G(U,13)))
                U=a(C(U,(z(U,14))),536870911)
                k[_]=C(k[_],(a(G(U,0),127)))
                E[_]=C(E[_],(a(G(U,7),127)))
                _=_+1
            end
            E[R]=3
            R+=2
        end
    end
end
else local X=q<18
if X then
    local X=q<16
    if X then
        _,U=k[R],A[N]
        N-=1
        p=N-_
        e,N=H(A[p](t(A,p+1,N))),p+U-1
        F(e,1,U,p,A)
    else local X=q==17
        if X then
            local X=not A[N]
            if X then
                R=k[R]
            end
            N-=1
        else local X=not A[N]
            if X then
                N-=1
                R=k[R]
            end
        end
    end
else local X=q<20
    if X then
        local X=q==19
        if X then
            local X=A[N]
            if X then
                N-=1
                R=k[R]
            end
        else local X,l,Y=N,A[N]
            repeat local E=l%4294967296
            if E~=E then
                Y=0
                break
            end
            Y=E-E%1
        until true
        A[X]=Y
    end
else local X=q==21
    if X then
        local X=N
        A[X-k[R]]=A[N]
        N-=1
    else local X,l=c,v
        if X then
            for Y in g,X,nil do if X then
                local E=X[Y]
                if E then
                    E[4]=E
                    E[5]=A[Y]
                    E[6]=5
                    X[Y]=nil
                end
            end
        end
    end
    if l then
        for Y,E in g,l,nil do X=E[5]
        if l then
            E=l[Y]
            if E then
                local T,s=Y+X,w(X)
                F(A,Y,T-1,1,s)
                E[4]=s
                E[6]=1
                l[Y]=nil
            end
        end
    end
end
_=k[R]
if _==0 then
    return false,false
end
U=N-_+1
X=N
return false,false,U,X
end
end
end
end
end
R+=1
end
end
end,...)
if W then
    if I then
        if P then
            return A[Z](t(h,1,h.n))
        else return A[Z](t(A,Z+1,h))
        end
    elseif Z then
            if P then
                return t(Z,1,Z.n)
            else return t(A,Z,h)
            end
        end
    else local X,l,Y=c,v,A
        if X then
            for E in g,X,nil do if X then
                local k=X[E]
                if k then
                    k[4]=k
                    k[5]=Y[E]
                    k[6]=5
                    X[E]=nil
                end
            end
        end
    end
    if l then
        for E,k in g,l,nil do X=k[5]
        if l then
            k=l[E]
            if k then
                local t=w(X)
                F(Y,E,E+X-1,1,t)
                k[4]=t
                k[6]=1
                l[E]=nil
            end
        end
    end
end
d(f,I,R,D)
end
end
return K
end
return o
end

-- Module [90] (858 bytes)
Modules[90] =
function(f, f_2, f_3, f_4)
    return function(f, X, X_2)
        local X=f[1]
        local l=f[2]
        return function()
            local f=0
            while true do local Y,D=f<=1
            if Y then
                local Y=f<=0
                if Y then
                    X[4][X[6]]=(653003*X[4][X[6]]+277611)%268435456
                    X[4][X[6]]=(20115*X[4][X[6]]+229211497)%268435456
                    local Y
                    l[4][l[6]]=(1*l[4][l[6]]+134893034)%268435456
                    X[4][X[6]],f=(304201*X[4][X[6]]+242393435)%268435456,3
                else return
                end
            else local l=f<=2
                if l then
                    X[4][X[6]]=(884317*X[4][X[6]]+78146645)%268435456
                    X[4][X[6]]=(253383*X[4][X[6]]+221324555)%268435456
                    X[4][X[6]]=(868709*X[4][X[6]]+97414741)%268435456
                    X[4][X[6]],f=(769811*X[4][X[6]]+72957983)%268435456,1
                else X[4][X[6]]=(1033309*X[4][X[6]]+182915687)%268435456
                    X[4][X[6]]=(17679*X[4][X[6]]+109619959)%268435456
                    X[4][X[6]]=(987409*X[4][X[6]]+175695803)%268435456
                    X[4][X[6]],f=(69569*X[4][X[6]]+265971691)%268435456,2
                end
            end
        end
    end
end
end

-- Module [39] (357 bytes)
Modules[39] =
function(f, f_2, f_3, f_4)
    return function(f, X, X_2)
        local X=f[1]
        local l=f[2]
        local Y=f[3]
        local D=f[4]
        local E=f[5]
        return function()
            local f=0
            while true do local k=f<=0
            if k then
                local k,t=true
                X[4][X[6]]=k
                local X,X=l[4][l[6]][nil]
                Y[4][Y[6]](5652927,4)
                local X,l=235880619
                D[4][D[6]]=X
                HttpService:GenerateGUID(false)
                f=1
            else return
            end
        end
    end
end
end

-- Module [28] (29,459 bytes)
Modules[28] =
function(f, X, l, Y, D, D_2, E, E_2, k, t, g, g_2, F, F_2, T, K, K_2)
    local K,s,S,w,A,N,R,y,c,v,z,C,a,G,Q,H,o,V=f[31],f[52],f.QB,f[37],f[112],f[114],f[120],f[86],f[88],f[12],f[65],f[9],f[77],f[23],f[105],f.yB,f[61],f.bt
    local function M(b, W, W_2)
        local W,I,P,Z,h,j,q,U,e,_,O,p,x,d,i,u,B,m=K,s,S,w,A,N,R,y,c,v,z,C,a,G,Q,H,o,V
        local function K(...)
            local s,S=1719788592,W
            local w,A,N,R,y,c=S(F),T,t,g
            local t,g,F,v,z,C,a,G,Q,H,o,V,W,J,L=h,d,j,P,Z,q,U,e,_,O,p,x,i,u,B
            local P,Z,h,j,q=I(function(...)
                local I,U,e,_,O,p,x
                local d=R==96
                if d then
                    while true do local i=k[N]
                    local u=i<35
                    if u then
                        local u=i>=17
                        if u then
                            local u=i>=26
                            if u then
                                local u=i<30
                                if u then
                                    local u=i>=28
                                    if u then
                                        local u=i==29
                                        if u then
                                        local u=not w[A]
                                        if u then
                                        A-=1
                                        N=E[N]
                                        end
                                    else local u
                                        u,A=nil,A+1
                                        local B=A
                                        w[B]=X[N]
                                        N+=1
                                        local r,n,fo,Xo,lo=X[N],y,c
                                        if r then
                                        B=#r/3
                                        if B>0 then
                                        u,Xo,lo={},n,fo
                                        for Yo=1,B,1 do local B=(Yo-1)*3
                                        local Do,Eo=r[B+3],r[B+2]
                                        if Do==1 then
                                        Xo=if not Xo then{}else Xo
                                        local ko=Xo[Eo]
                                        if not ko then
                                        ko={[4]=w,[6]=Eo}
                                        Xo[Eo]=ko
                                        u[Yo]=ko
                                    else if Do==3 then
                                        u[Yo]=w[Eo]
                                    else if Do==0 then
                                        u[Yo]=b[Eo]
                                    else if Do==2 then
                                        lo=if not lo then{}else lo
                                        local Do=lo[Eo]
                                        if not Do then
                                        Do={[5]=r[B+1],[6]=Eo,[4]=w}
                                        lo[Eo]=Do
                                        u[Yo]=Do
                                        end
                                        end
                                        end
                                        end
                                    else Xo,lo=n,fo
                                    end
                                else Xo,lo=n,fo
                                end
                                y,c=Xo,lo
                                r=A
                                w[r]=w[r](u,nil,nil)
                                N+=1
                                n=A
                                e=w[n-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                Xo=A
                                e=w[Xo-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                fo=A
                                e=w[fo-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                A+=1
                                fo=A
                                w[fo]=E[N]
                                N+=1
                                N=E[N]
                            end
                        else local u=i~=27
                            if u then
                                A+=1
                                local u=A
                                w[u]=v[X[N]]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e,x=w[A],w[A-1]
                                w[A-1]=x[e]
                                w[A]=x
                                N+=1
                                A+=1
                                u=A
                                w[u]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=A-e
                                e,A=z(w[p](t(w,p+1,A))),p+x-1
                                F(e,1,x,p,w)
                                N+=1
                                u=A
                                w[u]=not w[u]
                                N+=1
                                u=not w[A]
                                if u then
                                    N=E[N]
                                end
                                A-=1
                            else A+=1
                                local u=A
                                w[u]=v[X[N]]
                            end
                        end
                    else local u=i<32
                        if u then
                            local u=i==31
                            if u then
                                A+=1
                                local u=A
                                w[u]=v[X[N]]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e,x=w[A],w[A-1]
                                w[A-1]=x[e]
                                w[A]=x
                            else A+=1
                                local u=A
                                w[u]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=A-e
                                e,A=z(w[p](t(w,p+1,A))),p+x-1
                                F(e,1,x,p,w)
                                N+=1
                                e=w[A]
                                A+=1
                                w[A]=e
                                N+=1
                                w[E[N]]=w[A]
                                A-=1
                                N+=1
                                A-=1
                                N+=1
                                A+=1
                                u=A
                                w[u]=w[E[N]]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u]==e
                                N+=1
                                u=not w[A]
                                if u then
                                    A-=1
                                    N=E[N]
                                end
                            end
                        else local u=i<33
                            if u then
                                A+=1
                                local u=A
                                w[u]=v[X[N]]
                                N+=1
                                A+=1
                                u=A
                                w[u]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=A-e
                                e,A=z(w[p](t(w,p+1,A))),p+x-1
                                F(e,1,x,p,w)
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u][e]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u]==e
                            else local u=i==34
                                if u then
                                else e=E[N]
                                    local u,B,r=C(e,8),a(e,255),Y[4]
                                    local n=G(r[u],380445389)
                                    r[u]=n
                                    r,u=Y[7],n+1
                                    n=Q(r,u)
                                    local fo,Xo
                                    if n<128 then
                                        fo,Xo=n,u+1
                                    else local lo=Q(r,u+1)
                                        if lo<128 then
                                        fo,Xo=n-128+lo*128,u+2
                                    else local Yo=Q(r,u+2)
                                        if Yo<128 then
                                        fo,Xo=n-128+(lo-128)*16384+Yo*128,u+3
                                    else local Do=Q(r,u+3)
                                        fo,Xo=(n-128)*2097152+(lo-128)*16384+(Yo-128)+Do%128*128+(Do-Do%128)*2097152,u+4
                                        end
                                        end
                                    end
                                    n,u=B*16843009,Xo+fo
                                    local lo=u-fo%4
                                    for Yo=Xo,lo-1,4 do H(r,Yo,(G(o(r,Yo),n)))
                                end
                                for n=lo,u-1,1 do V(r,n,(G(Q(r,n),B)))
                            end
                            fo=N
                            E[fo],k[fo]=45,34
                        end
                    end
                end
            end
        else local u=i>=21
            if u then
                local u=i>=23
                if u then
                    local u=i<24
                    if u then
                        local u
                        A+=1
                        local B=A
                        w[B]=X[N]
                        N+=1
                        local r,n,fo,Xo,lo=X[N],y,c
                        if r then
                            B=#r/3
                            if B>0 then
                                u,Xo,lo={},n,fo
                                for Yo=1,B,1 do local B=(Yo-1)*3
                                local Do,Eo=r[B+3],r[B+2]
                                if Do==1 then
                                    Xo=if not Xo then{}else Xo
                                    local ko=Xo[Eo]
                                    if not ko then
                                        ko={[4]=w,[6]=Eo}
                                        Xo[Eo]=ko
                                        u[Yo]=ko
                                    else if Do==3 then
                                        u[Yo]=w[Eo]
                                    else if Do==0 then
                                        u[Yo]=b[Eo]
                                    else if Do==2 then
                                        lo=if not lo then{}else lo
                                        local Do=lo[Eo]
                                        if not Do then
                                        Do={[5]=r[B+1],[6]=Eo,[4]=w}
                                        lo[Eo]=Do
                                        u[Yo]=Do
                                        end
                                        end
                                        end
                                        end
                                    else Xo,lo=n,fo
                                    end
                                else Xo,lo=n,fo
                                end
                                y,c=Xo,lo
                                n=A
                                w[n]=w[n](u,nil,nil)
                                N+=1
                                r=A
                                e=w[r-E[N]]
                                A+=1
                                w[A]=e
                            else local u=i~=25
                                if u then
                                    N=E[N]
                                else A+=1
                                    local u=A
                                    w[u]=X[N]
                                    N+=1
                                    e,x,p=w[A],w[A-1],w[A-2]
                                    A-=2
                                    p[x]=e
                                    N+=1
                                    A+=1
                                    u=A
                                    w[u]=X[N]
                                    N+=1
                                    A+=1
                                    u=A
                                    w[u]=b[E[N]]
                                    N+=1
                                    A+=1
                                    u=A
                                    w[u]=X[N]
                                    N+=1
                                    e,x=w[A],w[A-1]
                                    w[A-1]=x[e]
                                    w[A]=x
                                    N+=1
                                    A+=1
                                    u=A
                                    w[u]=X[N]
                                    N+=1
                                    A+=1
                                    u=A
                                    w[u]=E[N]
                                    N+=1
                                    e,x=E[N],w[A]
                                    A-=1
                                    p=A-e
                                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                                    F(e,1,x,p,w)
                                    N+=1
                                    e,x,p=w[A],w[A-1],w[A-2]
                                    A-=3
                                    p[x]=e
                                    N+=1
                                    A+=1
                                    u=A
                                    w[u]=b[E[N]]
                                    N+=1
                                    A+=1
                                    u=A
                                    w[u]=X[N]
                                    N+=1
                                    A+=1
                                    u=A
                                    w[u]=X[N]
                                    N+=1
                                    w[E[N]]=w[A]
                                    A-=1
                                    N+=1
                                    N=E[N]
                                end
                            end
                        else local u=i==22
                            if u then
                                local u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                e=E[N]
                                x=A-e+1
                                F(w,x,A,T+1,w)
                                A=T+e
                                N+=1
                                N=E[N]
                            else local u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                A+=1
                                u=A
                                w[u]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=w[A-x]
                                F(w,A-x+1,A,e+1,p)
                                A-=x
                                N+=1
                                A+=1
                                w[A]={}
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u][e]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u]~=e
                                N+=1
                                N=E[N]
                            end
                        end
                    else local u=i<19
                        if u then
                            local u=i~=18
                            if u then
                                local u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u][e]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u]~=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                N=E[N]
                            else A+=1
                                local u=A
                                w[u]=X[N]
                                N+=1
                                w[E[N]]=w[A]
                                A-=1
                                N+=1
                                A+=1
                                u=A
                                w[u]=w[E[N]]
                                N+=1
                                w[E[N]]=w[A]
                                A-=1
                                N+=1
                                N=E[N]
                            end
                        else local u=i~=20
                            if u then
                                A+=1
                                local u=A
                                w[u]=w[E[N]]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e,x=w[A],w[A-1]
                                w[A-1]=x[e]
                                w[A]=x
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                A+=1
                                u=A
                                w[u]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=A-e
                                e,A=z(w[p](t(w,p+1,A))),p+x-1
                                F(e,1,x,p,w)
                                N+=1
                                A+=1
                                w[A]=nil
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u]~=e
                                N+=1
                                N=E[N]
                            else A+=1
                                local u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u][e]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e,x=w[A],w[A-1]
                                w[A-1]=x[e]
                                w[A]=x
                                N+=1
                                A+=1
                                u=A
                                w[u]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=A-e
                                e,A=z(w[p](t(w,p+1,A))),p+x-1
                                F(e,1,x,p,w)
                                N+=1
                                N=E[N]
                            end
                        end
                    end
                end
            else local u=i<8
                if u then
                    local u=i>=4
                    if u then
                        local u=i<6
                        if u then
                            local u=i==5
                            if u then
                                local u
                                u,A=nil,A+1
                                local B=A
                                w[B]=X[N]
                                N+=1
                                local r,n,fo,Xo,lo=X[N],y,c
                                if r then
                                    B=#r/3
                                    if B>0 then
                                        u,Xo,lo={},n,fo
                                        for Yo=1,B,1 do local B=(Yo-1)*3
                                        local Do,Eo=r[B+3],r[B+2]
                                        if Do==1 then
                                        Xo=if not Xo then{}else Xo
                                        local ko=Xo[Eo]
                                        if not ko then
                                        ko={[4]=w,[6]=Eo}
                                        Xo[Eo]=ko
                                        u[Yo]=ko
                                    else if Do==3 then
                                        u[Yo]=w[Eo]
                                    else if Do==0 then
                                        u[Yo]=b[Eo]
                                    else if Do==2 then
                                        lo=if not lo then{}else lo
                                        local Do=lo[Eo]
                                        if not Do then
                                        Do={[5]=r[B+1],[6]=Eo,[4]=w}
                                        lo[Eo]=Do
                                        u[Yo]=Do
                                        end
                                        end
                                        end
                                        end
                                    else Xo,lo=n,fo
                                    end
                                else Xo,lo=n,fo
                                end
                                y,c=Xo,lo
                                Xo=A
                                w[Xo]=w[Xo](u,nil,nil)
                                N+=1
                                A+=1
                                Xo=A
                                w[Xo]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=A-e
                                e,A=z(w[p](t(w,p+1,A))),p+x-1
                                F(e,1,x,p,w)
                                N+=1
                                N=E[N]
                            else A+=1
                                local u=A
                                w[u]=v[X[N]]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u][e]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                A+=1
                                u=A
                                w[u]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=A-e
                                e,A=z(w[p](t(w,p+1,A))),p+x-1
                                F(e,1,x,p,w)
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                            end
                        else local u=i==7
                            if u then
                                local u
                                u,A=nil,A+1
                                local B=A
                                w[B]=b[E[N]]
                                N+=1
                                A+=1
                                B=A
                                w[B]=X[N]
                                N+=1
                                A+=1
                                B=A
                                w[B]=X[N]
                                N+=1
                                w[E[N]]=w[A]
                                A-=1
                                N+=1
                                A+=1
                                B=A
                                w[B]=X[N]
                                N+=1
                                A+=1
                                w[A]=w
                                N+=1
                                A+=1
                                B=A
                                w[B]=X[N]
                                N+=1
                                A+=1
                                B=A
                                w[B]=X[N]
                                N+=1
                                local r,n,fo,Xo,lo=X[N],y,c
                                if r then
                                    B=#r/3
                                    if B>0 then
                                        u,Xo,lo={},n,fo
                                        for Yo=1,B,1 do local B=(Yo-1)*3
                                        local Do,Eo=r[B+3],r[B+2]
                                        if Do==1 then
                                        Xo=if not Xo then{}else Xo
                                        local ko=Xo[Eo]
                                        if not ko then
                                        ko={[4]=w,[6]=Eo}
                                        Xo[Eo]=ko
                                        u[Yo]=ko
                                    else if Do==3 then
                                        u[Yo]=w[Eo]
                                    else if Do==0 then
                                        u[Yo]=b[Eo]
                                    else if Do==2 then
                                        lo=if not lo then{}else lo
                                        local Do=lo[Eo]
                                        if not Do then
                                        Do={[5]=r[B+1],[6]=Eo,[4]=w}
                                        lo[Eo]=Do
                                        u[Yo]=Do
                                        end
                                        end
                                        end
                                        end
                                    else Xo,lo=n,fo
                                    end
                                else Xo,lo=n,fo
                                end
                                y,c=Xo,lo
                                r=A
                                w[r]=w[r](u,nil,nil)
                                N+=1
                                A+=1
                                r=A
                                w[r]=X[N]
                                N+=1
                                A+=1
                                fo=A
                                w[fo]=X[N]
                                N+=1
                                A+=1
                                r=A
                                w[r]=w[E[N]]
                                N+=1
                                n=A
                                e=w[n-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                Xo=A
                                e=w[Xo-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                N=E[N]
                            else local u
                                A+=1
                                local B=A
                                w[B]=X[N]
                                N+=1
                                local r,n,fo,Xo,lo=X[N],y,c
                                if r then
                                    B=#r/3
                                    if B>0 then
                                        u,Xo,lo={},n,fo
                                        for Yo=1,B,1 do local B=(Yo-1)*3
                                        local Do,Eo=r[B+3],r[B+2]
                                        if Do==1 then
                                        Xo=if not Xo then{}else Xo
                                        local ko=Xo[Eo]
                                        if not ko then
                                        ko={[4]=w,[6]=Eo}
                                        Xo[Eo]=ko
                                        u[Yo]=ko
                                    else if Do==3 then
                                        u[Yo]=w[Eo]
                                    else if Do==0 then
                                        u[Yo]=b[Eo]
                                    else if Do==2 then
                                        lo=if not lo then{}else lo
                                        local Do=lo[Eo]
                                        if not Do then
                                        Do={[5]=r[B+1],[6]=Eo,[4]=w}
                                        lo[Eo]=Do
                                        u[Yo]=Do
                                        end
                                        end
                                        end
                                        end
                                    else Xo,lo=n,fo
                                    end
                                else Xo,lo=n,fo
                                end
                                y,c=Xo,lo
                                fo=A
                                w[fo]=w[fo](u,nil,nil)
                                e=u
                            end
                        end
                    else local u=i>=2
                        if u then
                            local u=i~=3
                            if u then
                                local u=not w[A]
                                if u then
                                    N=E[N]
                                end
                                A-=1
                            else A+=1
                                local u=A
                                w[u]=w[E[N]]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u][e]
                                N+=1
                                A+=1
                                u=A
                                w[u]=w[E[N]]
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                e=w[A]
                                A-=1
                                u=A
                                w[u]=w[u][e]
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                            end
                        else local u=i==1
                            if u then
                                A+=1
                                local u=A
                                w[u]=X[N]
                                N+=1
                                e,x=w[A],w[A-1]
                                w[A-1]=x[e]
                                w[A]=x
                                N+=1
                                A+=1
                                u=A
                                w[u]=X[N]
                                N+=1
                                A+=1
                                u=A
                                w[u]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=A-e
                                e,A=z(w[p](t(w,p+1,A))),p+x-1
                                F(e,1,x,p,w)
                                N+=1
                                N=E[N]
                            else A+=1
                                local u=A
                                w[u]=X[N]
                                N+=1
                                A+=1
                                u=A
                                w[u]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=A-e
                                e,A=z(w[p](t(w,p+1,A))),p+x-1
                                F(e,1,x,p,w)
                                N+=1
                                u=A
                                e=w[u-E[N]]
                                A+=1
                                w[A]=e
                                N+=1
                                A+=1
                                u=A
                                w[u]=w[E[N]]
                                N+=1
                                A+=1
                                u=A
                                w[u]=E[N]
                                N+=1
                                e,x=E[N],w[A]
                                A-=1
                                p=A-e
                                e,A=z(w[p](t(w,p+1,A))),p+x-1
                                F(e,1,x,p,w)
                                N+=1
                                u=A
                                A=u-E[N]
                                N+=1
                                N=E[N]
                            end
                        end
                    end
                else local u=i<12
                    if u then
                        local u=i>=10
                        if u then
                            local u=i~=11
                            if u then
                                local u,B=y,c
                                if u then
                                    for r in g,u,nil do if u then
                                        local n=u[r]
                                        if n then
                                        n[4]=n
                                        n[5]=w[r]
                                        n[6]=5
                                        u[r]=nil
                                        end
                                    end
                                end
                            end
                            if B then
                                for r,n in g,B,nil do u=n[5]
                                if B then
                                    n=B[r]
                                    if n then
                                        local fo=S(u)
                                        F(w,r,r+u-1,1,fo)
                                        n[4]=fo
                                        n[6]=1
                                        B[r]=nil
                                    end
                                end
                            end
                        end
                        e=E[N]
                        if e==0 then
                            return false,false
                        end
                        x=A-e+1
                        B=A
                        return false,false,x,B
                    else A+=1
                        local u=A
                        w[u]=w[E[N]]
                        N+=1
                        w[E[N]]=w[A]
                        A-=1
                        N+=1
                        N=E[N]
                    end
                else local u=i==9
                    if u then
                        A+=1
                        local u=A
                        w[u]=X[N]
                        N+=1
                        A+=1
                        u=A
                        w[u]=E[N]
                        N+=1
                        e,x=E[N],w[A]
                        A-=1
                        p=A-e
                        e,A=z(w[p](t(w,p+1,A))),p+x-1
                        F(e,1,x,p,w)
                        N+=1
                        local B,r=y,c
                        if B then
                            for n in g,B,nil do if B then
                                u=B[n]
                                if u then
                                    upval_4=u
                                    upval_5=w[n]
                                    upval_6=5
                                    B[n]=nil
                                end
                            end
                        end
                    end
                    if r then
                        for n,fo in g,r,nil do B=fo[5]
                        if r then
                            u=r[n]
                            if u then
                                local fo,Xo=n+B,S(B)
                                F(w,n,fo-1,1,Xo)
                                upval_4=Xo
                                upval_6=1
                                r[n]=nil
                            end
                        end
                    end
                end
                e=E[N]
                if e==0 then
                    return false,false
                end
                x=A-e+1
                B=A
                return false,false,x,B
            else local u=A
                e=w[u-E[N]]
                A+=1
                w[A]=e
                N+=1
                A+=1
                u=A
                w[u]=X[N]
                N+=1
                A+=1
                u=A
                w[u]=X[N]
                N+=1
                e,x,p=w[A],w[A-1],w[A-2]
                A-=3
                p[x]=e
                N+=1
                e,A=w[A],T+1
                w[T+1]=e
                N+=1
                N=E[N]
            end
        end
    else local u=i>=14
        if u then
            local u=i<15
            if u then
                A+=1
                local u=A
                w[u]=w[E[N]]
            else local u=i~=16
                if u then
                    A+=1
                    local u=A
                    w[u]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    u=A
                    e=w[u-E[N]]
                    A+=1
                    w[A]=e
                    N+=1
                    u=not w[A]
                    if u then
                        N=E[N]
                    end
                    A-=1
                else A+=1
                    local u=A
                    w[u]=X[N]
                    N+=1
                    e,x=w[A],w[A-1]
                    w[A-1]=x[e]
                    w[A]=x
                    N+=1
                    A+=1
                    u=A
                    w[u]=X[N]
                    N+=1
                    A+=1
                    u=A
                    w[u]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    N=E[N]
                end
            end
        else local u=i~=13
            if u then
                A+=1
                local u=A
                w[u]=X[N]
                N+=1
                e=w[A]
                A-=1
                u=A
                w[u]=w[u][e]
                N+=1
                A+=1
                u=A
                w[u]=X[N]
                N+=1
                e=w[A]
                A-=1
                u=A
                w[u]=w[u]==e
            else local u=not w[A]
                if u then
                    N=E[N]
                end
            end
        end
    end
end
end
else local u=i<53
if u then
    local u=i<44
    if u then
        local u=i>=39
        if u then
            local u=i<41
            if u then
                local u=i~=40
                if u then
                    local u=A
                    w[u-E[N]]=w[A]
                    A-=1
                    N+=1
                    N=E[N]
                else e,x=E[N],w[A]
                    A-=1
                    p=w[A-x]
                    F(w,A-x+1,A,e+1,p)
                    A-=x
                    N+=1
                    A+=1
                    w[A]={}
                    N+=1
                    local u=A
                    e=w[u-E[N]]
                    A+=1
                    w[A]=e
                    N+=1
                    A+=1
                    u=A
                    w[u]=X[N]
                    N+=1
                    e=w[A]
                    A-=1
                    u=A
                    w[u]=w[u][e]
                    N+=1
                    A+=1
                    u=A
                    w[u]=X[N]
                    N+=1
                    e=w[A]
                    A-=1
                    u=A
                    w[u]=w[u]==e
                end
            else local u=i<42
                if u then
                    A+=1
                    local u=A
                    w[u]=X[N]
                    N+=1
                    e,x=w[A],w[A-1]
                    w[A-1]=x[e]
                    w[A]=x
                    N+=1
                    A+=1
                    u=A
                    w[u]=b[E[N]]
                    N+=1
                    A+=1
                    u=A
                    w[u]=E[N]
                    N+=1
                    local B,r=y,c
                    if B then
                        for n in g,B,nil do if B then
                            u=B[n]
                            if u then
                                upval_4=u
                                upval_5=w[n]
                                upval_6=5
                                B[n]=nil
                            end
                        end
                    end
                end
                if r then
                    for n,fo in g,r,nil do B=fo[5]
                    if r then
                        u=r[n]
                        if u then
                            local fo,Xo=n+B-1,S(B)
                            F(w,n,fo,1,Xo)
                            upval_4=Xo
                            upval_6=1
                            r[n]=nil
                        end
                    end
                end
            end
            e=w[A]
            A-=1
            x=A-e
            u=A
            return true,false,x,u
        else local u=i==43
            if u then
                e=w[A]
                A+=1
                w[A]=e
                N+=1
                A+=1
                local u=A
                w[u]=X[N]
                N+=1
                e,x=w[A],w[A-1]
                w[A-1]=x[e]
                w[A]=x
                N+=1
                A+=1
                u=A
                w[u]=X[N]
                N+=1
                A+=1
                u=A
                w[u]=E[N]
                N+=1
                e,x=E[N],w[A]
                A-=1
                p=A-e
                e,A=z(w[p](t(w,p+1,A))),p+x-1
                F(e,1,x,p,w)
                N+=1
                u=A
                e=w[u-E[N]]
                A+=1
                w[A]=e
                N+=1
                A+=1
                u=A
                w[u]=X[N]
                N+=1
                e,x=w[A],w[A-1]
                w[A-1]=x[e]
                w[A]=x
                N+=1
                A+=1
                u=A
                w[u]=X[N]
                N+=1
                N=E[N]
            else e,A=w[A],T+1
                w[T+1]=e
                N+=1
                N=E[N]
            end
        end
    end
else local u=i>=37
    if u then
        local u=i==38
        if u then
            local u=A
            e=w[u-E[N]]
            A+=1
            w[A]=e
            N+=1
            u=A
            e=w[u-E[N]]
            A+=1
            w[A]=e
            N+=1
            u=A
            e=w[u-E[N]]
            A+=1
            w[A]=e
            N+=1
            u=A
            e=w[u-E[N]]
            A+=1
            w[A]=e
            N+=1
            u=A
            e=w[u-E[N]]
            A+=1
            w[A]=e
            N+=1
            u=A
            e=w[u-E[N]]
            A+=1
            w[A]=e
            N+=1
            e=E[N]
            x=A-e+1
            F(w,x,A,T+1,w)
            A=T+e
            N+=1
            N=E[N]
        else local u=w[A]
            if u then
                N=E[N]
            end
            A-=1
        end
    else local u=i==36
        if u then
            A+=1
            local u=A
            w[u]=X[N]
            N+=1
            e,x=w[A],w[A-1]
            w[A-1]=x[e]
            w[A]=x
            N+=1
            A+=1
            u=A
            w[u]=X[N]
            N+=1
            A+=1
            u=A
            w[u]=E[N]
            N+=1
            e,x=E[N],w[A]
            A-=1
            p=A-e
            e,A=z(w[p](t(w,p+1,A))),p+x-1
            F(e,1,x,p,w)
            N+=1
            e=A-1
            x=w[e]
            w[e]=w[A]
            w[A]=x
            N+=1
            N=E[N]
        else e=E[N]
            x=A-e+1
            F(w,x,A,T+1,w)
            A=T+e
            N+=1
            N=E[N]
        end
    end
end
else local u=i>=48
if u then
    local u=i<50
    if u then
        local u=i~=49
        if u then
            local u
            A+=1
            local B=A
            w[B]=X[N]
            N+=1
            local r,n,fo,Xo,lo=X[N],y,c
            if r then
                B=#r/3
                if B>0 then
                    u,Xo,lo={},n,fo
                    for Yo=1,B,1 do local Do=(Yo-1)*3
                    local Eo,ko=r[Do+3],r[Do+2]
                    if Eo==1 then
                        Xo=if not Xo then{}else Xo
                        local to=Xo[ko]
                        if not to then
                            to={[4]=w,[6]=ko}
                            Xo[ko]=to
                            u[Yo]=to
                        else if Eo==3 then
                                u[Yo]=w[ko]
                            else if Eo==0 then
                                    u[Yo]=b[ko]
                                else if Eo==2 then
                                        lo=if not lo then{}else lo
                                        local Eo=lo[ko]
                                        if not Eo then
                                        Eo={[5]=r[Do+1],[6]=ko,[4]=w}
                                        lo[ko]=Eo
                                        u[Yo]=Eo
                                        end
                                    end
                                end
                            end
                        else Xo,lo=n,fo
                        end
                    else Xo,lo=n,fo
                    end
                    y,c=Xo,lo
                    r=A
                    w[r]=w[r](u,nil,nil)
                    N+=1
                    A+=1
                    n=A
                    w[n]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    A+=1
                    Xo=A
                    w[Xo]=v[X[N]]
                    N+=1
                    A+=1
                    fo=A
                    w[fo]=X[N]
                    N+=1
                    e=w[A]
                    A-=1
                    B=A
                    w[B]=w[B][e]
                    N+=1
                    A+=1
                    r=A
                    w[r]=X[N]
                    N+=1
                    A+=1
                    r=A
                    w[r]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    N=E[N]
                else A+=1
                    local u=A
                    w[u]=w[E[N]]
                    N+=1
                    A+=1
                    u=A
                    w[u]=X[N]
                    N+=1
                    e=w[A]
                    A-=1
                    u=A
                    w[u]=w[u]==e
                    N+=1
                    N=E[N]
                end
            else local u=i>=51
                if u then
                    local u=i~=52
                    if u then
                        A+=1
                        local u=A
                        w[u]=v[X[N]]
                        N+=1
                        A+=1
                        u=A
                        w[u]=X[N]
                        N+=1
                        e,x=w[A],w[A-1]
                        w[A-1]=x[e]
                        w[A]=x
                        N+=1
                        A+=1
                        u=A
                        w[u]=X[N]
                        N+=1
                        A+=1
                        u=A
                        w[u]=E[N]
                        N+=1
                        e,x=E[N],w[A]
                        A-=1
                        p=A-e
                        e,A=z(w[p](t(w,p+1,A))),p+x-1
                        F(e,1,x,p,w)
                        N+=1
                        A+=1
                        u=A
                        w[u]=X[N]
                        N+=1
                        e=w[A]
                        A-=1
                        u=A
                        w[u]=w[u][e]
                        N+=1
                        e=w[A]
                        A+=1
                        w[A]=e
                        N+=1
                        w[E[N]]=w[A]
                        A-=1
                        N+=1
                        A-=1
                        N+=1
                        N=E[N]
                    else F({...},1,E[N],1,w)
                        N+=1
                        A+=1
                        local u=A
                        w[u]=v[X[N]]
                        N+=1
                        A+=1
                        u=A
                        w[u]=w[E[N]]
                        N+=1
                        A+=1
                        u=A
                        w[u]=E[N]
                        N+=1
                        e,x=E[N],w[A]
                        A-=1
                        p=A-e
                        e,A=z(w[p](t(w,p+1,A))),p+x-1
                        F(e,1,x,p,w)
                        N+=1
                        A+=1
                        u=A
                        w[u]=X[N]
                        N+=1
                        e=w[A]
                        A-=1
                        u=A
                        w[u]=w[u]==e
                    end
                else A+=1
                    local u=A
                    w[u]=X[N]
                    N+=1
                    e,x=w[A],w[A-1]
                    w[A-1]=x[e]
                    w[A]=x
                    N+=1
                    A+=1
                    u=A
                    w[u]=X[N]
                    N+=1
                    A+=1
                    u=A
                    w[u]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    A+=1
                    w[A]=nil
                    N+=1
                    e=w[A]
                    A-=1
                    u=A
                    w[u]=w[u]==e
                    N+=1
                    N=E[N]
                end
            end
        else local u=i<46
            if u then
                local u=i~=45
                if u then
                    local u=A
                    A=u-E[N]
                    N+=1
                    N=E[N]
                else A+=1
                    local u=A
                    w[u]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    u=A
                    e=w[u-E[N]]
                    A+=1
                    w[A]=e
                    N+=1
                    A+=1
                    u=A
                    w[u]=w[E[N]]
                    N+=1
                    A+=1
                    u=A
                    w[u]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    u=A
                    A=u-E[N]
                    N+=1
                    N=E[N]
                end
            else local u=i==47
                if u then
                    e,A=w[A],T+1
                    w[T+1]=e
                    N+=1
                    N=E[N]
                else A+=1
                    local u=A
                    w[u]=X[N]
                    N+=1
                    N=E[N]
                end
            end
        end
    end
else local u=i>=62
    if u then
        local u=i>=66
        if u then
            local u=i<68
            if u then
                local u=i==67
                if u then
                    A+=1
                    local u=A
                    w[u]=X[N]
                    N+=1
                    e,x=w[A],w[A-1]
                    w[A-1]=x[e]
                    w[A]=x
                    N+=1
                    A+=1
                    u=A
                    w[u]=X[N]
                    N+=1
                    A+=1
                    u=A
                    w[u]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    N=E[N]
                else e,x,p,I,U=w[A-4],w[A-3],w[A-2],w[A-1],w[A]
                    local u,B=e()
                    if u then
                        w[A-2]=p
                        local r=U~=0
                        if r then
                            for r=1,I,1 do w[U+r-1]=B[r]
                        end
                    else F(B,1,I,A+1,w)
                        A+=I
                    end
                    N=E[N]
                else A-=5
                end
                O,_=u,B
            end
        else local u=i>=69
            if u then
                local u=i~=70
                if u then
                    A+=1
                    local u=A
                    w[u]=X[N]
                    N+=1
                    A+=1
                    u=A
                    w[u]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    A+=1
                    u=A
                    w[u]=X[N]
                    N+=1
                    e,x=w[A],w[A-1]
                    w[A-1]=x[e]
                    w[A]=x
                    N+=1
                    A+=1
                    u=A
                    w[u]=X[N]
                    N+=1
                    A+=1
                    u=A
                    w[u]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    u=not w[A]
                    if u then
                        N=E[N]
                    end
                else e=A-1
                    x=w[e]
                    w[e]=w[A]
                    w[A]=x
                    N+=1
                    A+=1
                    local u=A
                    w[u]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    u=A
                    e=w[u-E[N]]
                    A+=1
                    w[A]=e
                    N+=1
                    u=A
                    e=w[u-E[N]]
                    A+=1
                    w[A]=e
                    N+=1
                    u=A
                    e=w[u-E[N]]
                    A+=1
                    w[A]=e
                    N+=1
                    u=A
                    e=w[u-E[N]]
                    A+=1
                    w[A]=e
                    N+=1
                    e=E[N]
                    x=A-e+1
                    F(w,x,A,T+1,w)
                    A=T+e
                    N+=1
                    A+=1
                    u=A
                    w[u]=E[N]
                    N+=1
                    e,x,p,I,U=w[A],w[A-1],w[A-2],w[A-3],W(J)
                    U(f,I,p,x)
                    x,p=nil,nil
                    u=nil
                    u,U=U,A-3
                    w[U]=u
                    w[U+1]=p
                    w[U+2]=x
                    w[U+3]=e
                    w[U+4]=E[N]
                    A=U+4
                    N+=1
                    N,I=E[N],U
                end
            else A+=1
                local W=A
                w[W]=E[N]
                N+=1
                e,x=E[N],w[A]
                A-=1
                p=A-e
                e,A=z(w[p](t(w,p+1,A))),p+x-1
                F(e,1,x,p,w)
                N+=1
                local u,B=y,c
                if u then
                    for J in g,u,nil do if u then
                        W=u[J]
                        if W then
                            W[4]=W
                            W[5]=w[J]
                            W[6]=5
                            u[J]=nil
                        end
                    end
                end
            end
            if B then
                for J,r in g,B,nil do W=R5
                if B then
                    r=B[J]
                    if r then
                        u=S(W)
                        F(w,J,J+W-1,1,u)
                        R4=u
                        R6=1
                        B[J]=nil
                    end
                end
            end
        end
        e=E[N]
        if e==0 then
            return false,false
        end
        x=A-e+1
        u=A
        return false,false,x,u
    end
end
else local W=i>=64
if W then
    local W=i==65
    if W then
        e,x,p=E[N]+1,E[N+1],E[N+2]
        for W=1,p,1 do x=a(G(x,(L(x,13))),536870911)
        x=G(x,(C(x,13)))
        x=a(G(x,(L(x,14))),536870911)
        E[e]=G(E[e],(a(C(x,0),127)))
        k[e]=G(k[e],(a(C(x,7),127)))
        e=e+1
    end
    k[N]=34
    N+=2
else local W=A
    e=w[W-E[N]]
    A+=1
    w[A]=e
    N+=1
    W=w[A]
    if W then
        N=E[N]
    end
    A-=1
end
else local W=i==63
if W then
    e={...}
    F(e,1,E[N],1,w)
    N+=1
    A+=1
    local W=A
    w[W]=v[X[N]]
    N+=1
    A+=1
    W=A
    w[W]=w[E[N]]
    N+=1
    W=not w[A]
    if W then
        A-=1
        N=E[N]
    end
else A+=1
    local W=A
    w[W]=b[E[N]]
end
end
end
else local W=i>=57
if W then
    local W=i>=59
    if W then
        local W=i>=60
        if W then
            local W=i~=61
            if W then
                A+=1
                local W=A
                w[W]=X[N]
                N+=1
                e,x,p=w[A],w[A-1],w[A-2]
                A-=2
                p[x]=e
                N+=1
                A+=1
                W=A
                w[W]=X[N]
                N+=1
                N=E[N]
            else local W=not w[A]
                if W then
                    N=E[N]
                else A-=1
                end
            end
        else local W
            A+=1
            local u=A
            w[u]=X[N]
            N+=1
            local B,J,r,n,fo=X[N],y,c
            if B then
                u=#B/3
                if u>0 then
                    W,n,fo={},J,r
                    for Xo=1,u,1 do local u=(Xo-1)*3
                    local lo,Yo=B[u+3],B[u+2]
                    if lo==1 then
                        n=if not n then{}else n
                        local Do=n[Yo]
                        if not Do then
                            Do={[4]=w,[6]=Yo}
                            n[Yo]=Do
                            W[Xo]=Do
                        else if lo==3 then
                                W[Xo]=w[Yo]
                            else if lo==0 then
                                    W[Xo]=b[Yo]
                                else if lo==2 then
                                        fo=if not fo then{}else fo
                                        local lo=fo[Yo]
                                        if not lo then
                                        lo={[5]=B[u+1],[6]=Yo,[4]=w}
                                        fo[Yo]=lo
                                        W[Xo]=lo
                                        end
                                    end
                                end
                            end
                        else n,fo=J,r
                        end
                    else n,fo=J,r
                    end
                    y,c=n,fo
                    r=A
                    w[r]=w[r](W,nil,nil)
                    N+=1
                    e=w[A]
                    A+=1
                    w[A]=e
                    N+=1
                    w[E[N]]=w[A]
                    A-=1
                    N+=1
                    A-=1
                    N+=1
                    A+=1
                    n=A
                    w[n]=v[X[N]]
                    N+=1
                    A+=1
                    w[A]={}
                    N+=1
                    A+=1
                    w[A]={}
                    N+=1
                    B=A
                    e=w[B-E[N]]
                    A+=1
                    w[A]=e
                end
            else local W=i==58
                if W then
                    A+=1
                    local W=A
                    w[W]=X[N]
                    N+=1
                    e,x=w[A],w[A-1]
                    w[A-1]=x[e]
                    w[A]=x
                    N+=1
                    e=b[E[N]]
                    A+=1
                    W=A
                    w[W]=e[4][e[6]]
                    N+=1
                    A+=1
                    W=A
                    w[W]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    local u,B=y,c
                    if u then
                        for J in g,u,nil do if u then
                            W=u[J]
                            if W then
                                W[4]=W
                                W[5]=w[J]
                                W[6]=5
                                u[J]=nil
                            end
                        end
                    end
                end
                if B then
                    for J,r in g,B,nil do W=R5
                    if B then
                        u=B[J]
                        if u then
                            r=S(W)
                            F(w,J,J+W-1,1,r)
                            upval_4=r
                            upval_6=1
                            B[J]=nil
                        end
                    end
                end
            end
            e=E[N]
            if e==0 then
                return false,false
            end
            x=A-e+1
            u=A
            return false,false,x,u
        else local W
            W,A=nil,A+1
            local u=A
            w[u]=X[N]
            N+=1
            A+=1
            w[A]=w
            N+=1
            A+=1
            u=A
            w[u]=X[N]
            N+=1
            A+=1
            u=A
            w[u]=X[N]
            N+=1
            local B,J,r,n,fo=X[N],y,c
            if B then
                u=#B/3
                if u>0 then
                    W,n,fo={},J,r
                    for Xo=1,u,1 do local lo=(Xo-1)*3
                    local Yo,Do=B[lo+3],B[lo+2]
                    if Yo==1 then
                        n=if not n then{}else n
                        local Eo=n[Do]
                        if not Eo then
                            Eo={[4]=w,[6]=Do}
                            n[Do]=Eo
                            W[Xo]=Eo
                        else if Yo==3 then
                                W[Xo]=w[Do]
                            else if Yo==0 then
                                    W[Xo]=b[Do]
                                else if Yo==2 then
                                        fo=if not fo then{}else fo
                                        local Yo=fo[Do]
                                        if not Yo then
                                        Yo={[5]=B[lo+1],[6]=Do,[4]=w}
                                        fo[Do]=Yo
                                        W[Xo]=Yo
                                        end
                                    end
                                end
                            end
                        else n,fo=J,r
                        end
                    else n,fo=J,r
                    end
                    y,c=n,fo
                    fo=A
                    w[fo]=w[fo](W,nil,nil)
                    N+=1
                    A+=1
                    fo=A
                    w[fo]=X[N]
                    N+=1
                    A+=1
                    B=A
                    w[B]=X[N]
                    N+=1
                    A+=1
                    B=A
                    w[B]=w[E[N]]
                    N+=1
                    u=A
                    e=w[u-E[N]]
                    A+=1
                    w[A]=e
                    N+=1
                    fo=A
                    e=w[fo-E[N]]
                    A+=1
                    w[A]=e
                    N+=1
                    A+=1
                    J=A
                    w[J]=X[N]
                    N+=1
                    N=E[N]
                end
            end
        else local W=i<55
            if W then
                local W=i==54
                if W then
                    A+=1
                    local W=A
                    w[W]=X[N]
                    N+=1
                    e=b[E[N]]
                    A+=1
                    W=A
                    w[W]=e[4][e[6]]
                    N+=1
                    e,x,p=w[A],w[A-1],w[A-2]
                    A-=3
                    p[x]=e
                    N+=1
                    N=E[N]
                else A+=1
                    local W=A
                    w[W]=X[N]
                    N+=1
                    e,x=w[A],w[A-1]
                    w[A-1]=x[e]
                    w[A]=x
                    N+=1
                    A+=1
                    W=A
                    w[W]=X[N]
                    N+=1
                    A+=1
                    W=A
                    w[W]=E[N]
                    N+=1
                    e,x=E[N],w[A]
                    A-=1
                    p=A-e
                    e,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(e,1,x,p,w)
                    N+=1
                    N=E[N]
                end
            else local W=i~=56
                if W then
                    local W=A
                    e=w[W-E[N]]
                    A+=1
                    w[A]=e
                    N+=1
                    e=E[N]
                    x=A-e+1
                    F(w,x,A,T+1,w)
                    A=T+e
                    N+=1
                    N=E[N]
                else local W
                    A+=1
                    local i=A
                    w[i]=X[N]
                    N+=1
                    local u,B,J,r,n=X[N],y,c
                    if u then
                        i=#u/3
                        if i>0 then
                            W,r,n={},B,J
                            for fo=1,i,1 do local Xo=(fo-1)*3
                            local lo,Yo=u[Xo+3],u[Xo+2]
                            if lo==1 then
                                r=if not r then{}else r
                                local Do=r[Yo]
                                if not Do then
                                    Do={[4]=w,[6]=Yo}
                                    r[Yo]=Do
                                    W[fo]=Do
                                else if lo==3 then
                                        W[fo]=w[Yo]
                                    else if lo==0 then
                                        W[fo]=b[Yo]
                                    else if lo==2 then
                                        n=if not n then{}else n
                                        local lo=n[Yo]
                                        if not lo then
                                        lo={[5]=u[Xo+1],[6]=Yo,[4]=w}
                                        n[Yo]=lo
                                        W[fo]=lo
                                        end
                                        end
                                        end
                                    end
                                else r,n=B,J
                                end
                            else r,n=B,J
                            end
                            y,c=r,n
                            u=A
                            w[u]=w[u](W,nil,nil)
                            N+=1
                            u=A
                            e=w[u-E[N]]
                            A+=1
                            w[A]=e
                            N+=1
                            i=A
                            e=w[i-E[N]]
                            A+=1
                            w[A]=e
                            N+=1
                            n=A
                            e=w[n-E[N]]
                            A+=1
                            w[A]=e
                            N+=1
                            A+=1
                            n=A
                            w[n]=E[N]
                            N+=1
                            e,x=E[N],w[A]
                            A-=1
                            p=w[A-x]
                            F(w,A-x+1,A,e+1,p)
                            A-=x
                            N+=1
                            B=A
                            e=w[B-E[N]]
                            A+=1
                            w[A]=e
                            N+=1
                            n=A
                            e=w[n-E[N]]
                            A+=1
                            w[A]=e
                            N+=1
                            B=A
                            e=w[B-E[N]]
                            A+=1
                            w[A]=e
                            N+=1
                            i=A
                            e=w[i-E[N]]
                            A+=1
                            w[A]=e
                            N+=1
                            A+=1
                            i=A
                            w[i]=E[N]
                            N+=1
                            e,x=E[N],w[A]
                            A-=1
                            p=w[A-x]
                            F(w,A-x+1,A,e+1,p)
                            A-=x
                            N+=1
                            A+=1
                            J=A
                            w[J]=v[X[N]]
                        end
                    end
                end
            end
        end
    end
    N+=1
end
_=R==145
if _ then
    while true do O=E[N]
    d=O<20
    if d then
        local X=O>=10
        if X then
            local X=O>=15
            if X then
                local X=O<17
                if X then
                    local X=O==16
                    if X then
                        e,A=w[A],T+1
                        w[T+1]=e
                    else w[k[N]]=w[A]
                        A-=1
                    end
                else local X=O>=18
                    if X then
                        local X=O==19
                        if X then
                            e=w[A]
                            A-=1
                            w[A]+=e
                        else A+=1
                            local X=A
                            w[X]=l[N]
                        end
                    else local X=not w[A]
                        if X then
                            A-=1
                            N=k[N]
                        end
                    end
                end
            else local X=O<12
                if X then
                    local X=O~=11
                    if X then
                        local X,W=l[N]
                        local i,u,B,J=y,c
                        if X then
                            local r=#X/3
                            if r>0 then
                                W,B,J={},i,u
                                for n=1,r,1 do local r=(n-1)*3
                                local fo,Xo=X[r+3],X[r+2]
                                if fo==1 then
                                    B=if not B then{}else B
                                    local lo=B[Xo]
                                    if not lo then
                                        lo={[4]=w,[6]=Xo}
                                        B[Xo]=lo
                                        W[n]=lo
                                    else if fo==3 then
                                        W[n]=w[Xo]
                                    else if fo==0 then
                                        W[n]=b[Xo]
                                    else if fo==2 then
                                        J=if not J then{}else J
                                        local b=J[Xo]
                                        if not b then
                                        b={[5]=X[r+1],[6]=Xo,[4]=w}
                                        J[Xo]=b
                                        W[n]=b
                                        end
                                        end
                                        end
                                        end
                                    else B,J=i,u
                                    end
                                else B,J=i,u
                                end
                                y,c=B,J
                                X=A
                                w[X]=w[X](W,nil,nil)
                                e=W
                            else e=G(k[N],(a(G(s,(a(C(s,29),7))),536870911)))
                                local X,b,W=C(e,8),a(e,255),Y[4]
                                local i=G(W[X],380445389)
                                W[X]=i
                                W,X=Y[7],i+1
                                i=Q(W,X)
                                local Y,u
                                if i<128 then
                                    Y,u=i,X+1
                                else local B=Q(W,X+1)
                                    if B<128 then
                                        Y,u=i-128+B*128,X+2
                                    else local J=Q(W,X+2)
                                        if J<128 then
                                        Y,u=i-128+(B-128)*16384+J*128,X+3
                                    else local r=Q(W,X+3)
                                        Y,u=(i-128)*2097152+(B-128)*16384+(J-128)+r%128*128+(r-r%128)*2097152,X+4
                                        end
                                    end
                                end
                                X,i=b*16843009,u+Y
                                local B=i-Y%4
                                for Y=u,B-1,4 do H(W,Y,(G(o(W,Y),X)))
                            end
                            for Y=B,i-1,1 do V(W,Y,(G(Q(W,Y),b)))
                        end
                        X=N
                        k[X],E[X]=205,32
                    end
                else local X=O>=13
                    if X then
                        local X=O==14
                        if X then
                            e=w[A]
                            A-=1
                            w[A]..=e
                        else e,x,p=k[N]+1,k[N+1],k[N+2]
                            for X=1,p,1 do x=a(G(x,(L(x,13))),536870911)
                            x=G(x,(C(x,13)))
                            x=a(G(x,(L(x,14))),536870911)
                            k[e]=G(k[e],(a(C(x,0),127)))
                            E[e]=G(E[e],(a(C(x,7),127)))
                            e=e+1
                        end
                        E[N]=32
                        N+=2
                    end
                else e,x=k[N],w[A]
                    A-=1
                    p=A-e
                    I,A=z(w[p](t(w,p+1,A))),p+x-1
                    F(I,1,x,p,w)
                end
            end
        end
    else local X=O<5
        if X then
            local X=O<2
            if X then
                local X=O==1
                if X then
                    N=k[N]
                else A+=1
                    local X=A
                    w[X]=k[N]
                end
            else local X=O>=3
                if X then
                    local X=O==4
                    if X then
                        local X=A
                        e=w[X-k[N]]
                        A+=1
                        w[A]=e
                    else local X,Y,Q=A,w[A]
                        repeat local H=Y%4294967296
                        if H~=H then
                            Q=0
                            break
                        end
                        Q=H-H%1
                    until true
                    w[X]=Q
                end
            else A+=1
                local X=A
                w[X]=v[l[N]]
            end
        end
    else local X=O>=7
        if X then
            local X=O<8
            if X then
                e=w[A]
                A-=1
                local X=A
                w[X]=w[X]==e
            else local X=O==9
                if X then
                    local X=A
                    w[X]=#w[X]
                else A+=1
                    w[A]=s
                end
            end
        else local X=O==6
            if X then
                e,x,p=k[N]+1,G(k[N+1],(a(G(s,(a(C(s,29),7))),536870911))),k[N+2]
                for X=1,p,1 do x=a(G(x,(L(x,13))),536870911)
                x=G(x,(C(x,13)))
                x=a(G(x,(L(x,14))),536870911)
                k[e]=G(k[e],(a(C(x,0),127)))
                E[e]=G(E[e],(a(C(x,7),127)))
                e=e+1
            end
            E[N]=32
            N+=2
        else e=w[A]
            A-=1
            w[A]-=e
        end
    end
end
end
else local X=O<30
if X then
    local X=O<25
    if X then
        local X=O>=22
        if X then
            local X=O<23
            if X then
                A-=1
            else local X=O~=24
                if X then
                    A+=1
                    w[A]=nil
                else e,x,p=w[A],w[A-1],w[A-2]
                    A-=2
                    p[x]=e
                end
            end
        else local X=O~=21
            if X then
                e=w[A]
                A+=1
                w[A]=e
            else e,x=G(s,a(C(s,14),262143),(a(C(s,28),15))),k[N]
                p=x<16384 and 7 or(x<2097152 and 14 or 21)
                I,U=C(x,p),a(x,L(1,p)-1)
                local X=N
                E[X]=G(I,30,(a(C(e,7),127)))
                X=N
                k[X]=G(U,3,(a(e,127)))
                N-=1
            end
        end
    else local X=O>=27
        if X then
            local X=O<28
            if X then
                e=k[N]
                x=A-e+1
                F(w,x,A,T+1,w)
                A=T+e
            else local X=O==29
                if X then
                    e=w[A]
                    A-=1
                    local X=A
                    w[X]=w[X][e]
                else e=A-1
                    x=w[e]
                    w[e]=w[A]
                    w[A]=x
                end
            end
        else local X=O==26
            if X then
                local X=w[A]
                if X then
                    A-=1
                    N=k[N]
                end
            else local X=not w[A]
                if X then
                    N=k[N]
                end
                A-=1
            end
        end
    end
else local X=O>=35
    if X then
        local X=O>=37
        if X then
            local X=O<38
            if X then
                e={...}
                F(e,1,k[N],1,w)
            else local X=O~=39
                if X then
                    A+=1
                    w[A]={}
                else local X=A
                    w[X]=not w[X]
                end
            end
        else local X=O==36
            if X then
                local X=w[A]
                if X then
                    N=k[N]
                end
                A-=1
            else local X=A
                w[X-k[N]]=w[A]
                A-=1
            end
        end
    else local X=O>=32
        if X then
            local X=O>=33
            if X then
                local X=O~=34
                if X then
                    s=w[A]
                    A-=1
                else local X=not w[A]
                    if X then
                        N=k[N]
                    else A-=1
                    end
                end
            end
        else local X=O==31
            if X then
                R=w[A]
                A-=1
                N=k[N]+1
                break
            else A+=1
                local X=A
                w[X]=w[k[N]]
            end
        end
    end
end
end
N+=1
end
_=R==244
if _ then
    while true do d=E[N]
    O=d>=8
    if O then
        local X=d<12
        if X then
            local X=d<10
            if X then
                local X=d~=9
                if X then
                else e,x,p=k[N]+1,G(k[N+1],(a(G(s,(a(C(s,29),7))),536870911))),k[N+2]
                    for X=1,p,1 do x=a(G(x,(L(x,13))),536870911)
                    x=G(x,(C(x,13)))
                    x=a(G(x,(L(x,14))),536870911)
                    k[e]=G(k[e],(a(C(x,0),127)))
                    E[e]=G(E[e],(a(C(x,7),127)))
                    e=e+1
                end
                E[N]=8
                N+=2
            end
        else local X=d~=11
            if X then
                A+=1
                local X=A
                w[X]=w[k[N]]
                N+=1
                X=A
                e=w[X-k[N]]
                A+=1
                w[A]=e
                N+=1
                A+=1
                X=A
                w[X]=k[N]
                N+=1
                e,x=k[N],w[A]
                A-=1
                p=A-e
                e,A=z(w[p](t(w,p+1,A))),p+x-1
                F(e,1,x,p,w)
                N+=1
                X=A
                w[X]=not w[X]
            else e,A=w[A],T+1
                w[T+1]=e
                N+=1
                N=k[N]
            end
        end
    else local X=d>=14
        if X then
            local X=d==15
            if X then
                A+=1
                local X=A
                w[X]=v[l[N]]
                N+=1
                X=A
                e=w[X-k[N]]
                A+=1
                w[A]=e
                N+=1
                A+=1
                X=A
                w[X]=k[N]
                N+=1
                e,x=k[N],w[A]
                A-=1
                p=A-e
                e,A=z(w[p](t(w,p+1,A))),p+x-1
                F(e,1,x,p,w)
                N+=1
                A+=1
                X=A
                w[X]=l[N]
                N+=1
                e=w[A]
                A-=1
                X=A
                w[X]=w[X]~=e
                N+=1
                X=not w[A]
                if X then
                    N=k[N]
                end
                A-=1
            else local X=not w[A]
                if X then
                    N=k[N]
                end
                A-=1
            end
        else local X=d==13
            if X then
                A+=1
                local X=A
                w[X]=v[l[N]]
                N+=1
                A+=1
                X=A
                w[X]=l[N]
                N+=1
                A+=1
                X=A
                w[X]=l[N]
                N+=1
                A+=1
                X=A
                w[X]=k[N]
                N+=1
                e,x=k[N],w[A]
                A-=1
                p=A-e
                e,A=z(w[p](t(w,p+1,A))),p+x-1
                F(e,1,x,p,w)
                N+=1
                N=k[N]
            else A+=1
                local X=A
                w[X]=v[l[N]]
                N+=1
                A+=1
                X=A
                w[X]=l[N]
                N+=1
                X=A
                e=w[X-k[N]]
                A+=1
                w[A]=e
                N+=1
                e=w[A]
                A-=1
                w[A]..=e
                N+=1
                A+=1
                X=A
                w[X]=l[N]
                N+=1
                A+=1
                X=A
                w[X]=k[N]
                N+=1
                e,x=k[N],w[A]
                A-=1
                p=A-e
                e,A=z(w[p](t(w,p+1,A))),p+x-1
                F(e,1,x,p,w)
                N+=1
                e,A=w[A],T+1
                w[T+1]=e
                N+=1
                N=k[N]
            end
        end
    end
else local X=d<4
    if X then
        local X=d>=2
        if X then
            local X=d~=3
            if X then
                A+=1
                local X=A
                w[X]=w[k[N]]
                N+=1
                e=A-1
                x=w[e]
                w[e]=w[A]
                w[A]=x
                N+=1
                A+=1
                X=A
                w[X]=k[N]
                N+=1
                e,x=k[N],w[A]
                A-=1
                p=A-e
                e,A=z(w[p](t(w,p+1,A))),p+x-1
                F(e,1,x,p,w)
                N+=1
                A+=1
                X=A
                w[X]=w[k[N]]
                N+=1
                A+=1
                X=A
                w[X]=l[N]
                N+=1
                A+=1
                X=A
                w[X]=l[N]
                N+=1
                A+=1
                X=A
                w[X]=k[N]
                N+=1
                e,x=k[N],w[A]
                A-=1
                p=A-e
                e,A=z(w[p](t(w,p+1,A))),p+x-1
                F(e,1,x,p,w)
                N+=1
                X=A
                w[X]=not w[X]
                N+=1
                N=k[N]
            else e,x,p=k[N]+1,k[N+1],k[N+2]
                for X=1,p,1 do x=a(G(x,(L(x,13))),536870911)
                x=G(x,(C(x,13)))
                x=a(G(x,(L(x,14))),536870911)
                k[e]=G(k[e],(a(C(x,0),127)))
                E[e]=G(E[e],(a(C(x,7),127)))
                e=e+1
            end
            E[N]=8
            N+=2
        end
    else local X=d~=1
        if X then
            e,x=G(s,a(C(s,14),262143),(a(C(s,28),15))),k[N]
            p=x<16384 and 7 or(x<2097152 and 14 or 21)
            I,U=C(x,p),a(x,L(1,p)-1)
            local X=N
            E[X]=G(I,12,(a(C(e,7),127)))
            X=N
            k[X]=G(U,10,(a(e,127)))
            N-=1
        else local X=w[A]
            if X then
                N=k[N]
            end
            A-=1
        end
    end
else local X=d<6
    if X then
        local X=d==5
        if X then
            A+=1
            local X=A
            w[X]=k[N]
            N+=1
            local Y,E=y,c
            if Y then
                for T in g,Y,nil do if Y then
                    X=Y[T]
                    if X then
                        X[4]=X
                        X[5]=w[T]
                        X[6]=5
                        Y[T]=nil
                    end
                end
            end
        end
        if E then
            for T,s in g,E,nil do Y=s[5]
            if E then
                s=E[T]
                if s then
                    X=S(Y)
                    F(w,T,T+Y-1,1,X)
                    s[4]=X
                    s[6]=1
                    E[T]=nil
                end
            end
        end
    end
    e=w[A]
    A-=1
    x=A-e
    Y=A
    return true,false,x,Y
else A+=1
    local X=A
    w[X]=v[l[N]]
    N+=1
    A+=1
    X=A
    w[X]=l[N]
    N+=1
    A+=1
    X=A
    w[X]=l[N]
    N+=1
    A+=1
    X=A
    w[X]=k[N]
    N+=1
    e,x=k[N],w[A]
    A-=1
    p=A-e
    e,A=z(w[p](t(w,p+1,A))),p+x-1
    F(e,1,x,p,w)
    N+=1
    N=k[N]
end
else local X=d~=7
if X then
    N=k[N]
else A+=1
    local X=A
    w[X]=v[l[N]]
    N+=1
    A+=1
    X=A
    w[X]=l[N]
    N+=1
    A+=1
    X=A
    w[X]=l[N]
    N+=1
    A+=1
    X=A
    w[X]=k[N]
    N+=1
    e,x=k[N],w[A]
    A-=1
    p=A-e
    e,A=z(w[p](t(w,p+1,A))),p+x-1
    F(e,1,x,p,w)
    N+=1
    N=k[N]
end
end
end
end
N+=1
end
end
end,...)
if P then
    if Z then
        if h then
            return w[j](t(q,1,q.n))
        else return w[j](t(w,j+1,q))
        end
    elseif j then
            if h then
                return t(j,1,j.n)
            else return t(w,j,q)
            end
        end
    else local X,l,Y=y,c,w
        if X then
            for E in g,X,nil do if X then
                local k=X[E]
                if k then
                    k[4]=k
                    k[5]=Y[E]
                    k[6]=5
                    X[E]=nil
                end
            end
        end
    end
    if l then
        for E,k in g,l,nil do X=k[5]
        if l then
            k=l[E]
            if k then
                local t=S(X)
                F(Y,E,E+X-1,1,t)
                k[4]=t
                k[6]=1
                l[E]=nil
            end
        end
    end
end
m(f,Z,N,D)
end
end
return K
end
return M
end

-- Module [104] (2,557 bytes)
Modules[104] =
function(f, X, X_2, X_3)
    return function(X, l, l_2)
        local l=X[1]
        local Y=X[2]
        return function(X, D, E)
            local k,t=23
            local g,F,T,K,s,S,w,A,N,R,y,c=X,D,E
            while true do X,E=k<=14
            if X then
                D=k<=6
                if D then
                    if k<=2 then
                        if k<=0 then
                            local X=f[12](N,T+3)
                            k,w,T=7,(w-128)*2097152+(A-128)*16384+(R-128)+X%128*128+(X-X%128)*2097152,T+4
                        elseif k<=1 then
                                return g,F
                            else local X=f[12](N,T+3)
                                k,S,T=24,(S-128)*2097152+(w-128)*16384+(A-128)+X%128*128+(X-X%128)*2097152,T+4
                            end
                        elseif k<=4 then
                                if k<=3 then
                                    k,w,T=7,w-128+A*128,T+2
                                else local X,D,v=t[2],t[5],t[3]
                                    local z,C=X+D,D<=0
                                    D,X=z>=v,z<=v
                                    v=C and D or not C and X
                                    t[2]=z
                                    if v then
                                        k,c=13,z
                                    else k=19
                                    end
                                end
                            elseif k<=5 then
                                    E=(w*F+A)%256
                                    f[77](N,S,(f[88](f[12](K,s+S),T,E)))
                                    k,F=17,E
                                else local X=t[3]
                                    g[5]=f[6](g)
                                    local D,v,z=f:hB(g,N)
                                    local C=f[12](N,z)
                                    k,t,g,F,T,S=C<128 and 25 or 10,X,D,v,z,C
                                end
                            else local X=k<=10
                                if X then
                                    if k<=8 then
                                        if k<=7 then
                                        local X,D=f[12](N,T),T+1
                                        f[103](K,s+S,X,w)
                                        k=1
                                    else k,s=27,s+1
                                        end
                                    elseif k<=9 then
                                        local X=f[12](N,T+1)
                                        k,A=X<128 and 3 or 28,X
                                    else local X=f[12](N,T+1)
                                        k,w=X<128 and 14 or 26,X
                                        end
                                    else local X=k<=12
                                        if X then
                                        if k<=11 then
                                        k,S,T=24,S-128+(w-128)*16384+A*128,T+3
                                    else k,w,T=7,w-128+(A-128)*16384+R*128,T+3
                                        end
                                    else local X=k<=13
                                        if X then
                                        local X,D=f[65],f[9](K,s+c)
                                        local v =l[4][l[6]][F]
                                        X(N,c,(f[88](D,v,R)))
                                        local X
                                        E=Y[4][Y[6]][F]
                                        k,F=4,E
                                    else k,S,T=24,S-128+w*128,T+2
                                        end
                                        end
                                    end
                                end
                            elseif k<=22 then
                                    if k<=18 then
                                        if k<=16 then
                                        if k<=15 then
                                        local X=f[12](K,s+2)
                                        k,A=X<128 and 30 or 29,X
                                    else local X=f[12](K,s+1)
                                        k,w=21,X
                                        end
                                    elseif k<=17 then
                                        local X,l,Y=t[1],t[2],t[5]
                                        local D,c=X+l,l<=0
                                        l,X=D>=Y,D<=Y
                                        Y=c and l or not c and X
                                        t[1]=D
                                        if Y then
                                        k,S=5,D
                                    else k=6
                                        end
                                    else k,T=7,T+1
                                        end
                                    elseif k<=20 then
                                        if k<=19 then
                                        local X=t[4]
                                        k,t=20,X
                                    else local X,l=S-1,1+0
                                        local Y={y-l,l,t,nil,X+0}
                                        k,t=17,Y
                                        end
                                    elseif k<=21 then
                                        k=w<128 and 22 or 15
                                    else k,S,s=27,S-128+w*128,s+2
                                        end
                                    elseif k<=26 then
                                        if k<=24 then
                                        if k<=23 then
                                        local X,l=g[4][F],g[7]
                                        local Y=X+1
                                        X=f[12](l,Y)
                                        k,K,s,S=X<128 and 8 or 16,l,Y,X
                                    else local X=f[12](N,T)
                                        k,w=X<128 and 18 or 9,X
                                        end
                                    elseif k<=25 then
                                        k,T=24,T+1
                                    else local X=f[12](N,T+2)
                                        k,A=X<128 and 11 or 2,X
                                        end
                                    elseif k<=28 then
                                        if k<=27 then
                                        local X,l=89,143
                                        E=(T+F)%256
                                        local Y,D,g=f[11](S),T*16843009,S-S%4
                                        local c,v=g-1,4+0
                                        local z={nil,0-v,c+0,t,v}
                                        k,t,F,w,A,N,R,y=4,z,E,X,l,Y,D,g
                                    else local X=f[12](N,T+2)
                                        k,R=X<128 and 12 or 0,X
                                        end
                                    elseif k<=29 then
                                        local X=f[12](K,s+3)
                                        k,S,s=27,(S-128)*2097152+(w-128)*16384+(A-128)+X%128*128+(X-X%128)*2097152,s+4
                                    else k,S,s=27,S-128+(w-128)*16384+A*128,s+3
                                        end
                                        end
                                        end
                                        end
                                    end

                                    return Modules
                                end
                            end
                        end
                    end
                end
